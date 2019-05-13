Docker image 實作範例

打包：docker build -t helloworld .

運行：docker run -p 4000:80 helloworld

tag準備發布上Docker Hub: docker tag helloworld <your name>/helloworld:v1

發布上Docker Hub: docker push <your name>/helloworld:v1

