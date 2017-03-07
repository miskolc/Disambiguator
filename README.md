## kagglegym

    $ sudo docker build -t kagglegym .
    $ sudo docker run -it -v $(pwd):/wd -p 8888:8888 --memory="2g" --cpu-quota="50000" kagglegym jupyter notebook --port=8888 --ip=0.0.0.0