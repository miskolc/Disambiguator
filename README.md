## kagglegym

    $ sudo docker build -t kagglegym .
    $ sudo docker run -it -v $(pwd):/wd -p 8888:8888 --memory="2g" --cpu-quota="50000" kagglegym jupyter notebook --port=8888 --ip=0.0.0.0
    
    
## Testare

### Varianta Initiala

* hard  1165 / 4333  26.886%
* interest 779 / 2368 32.896%
* lines 1384 / 4146 33.38%
* serve 811/ 4378 18.524%

### Varianta cu noile perechi de relatii

* hard  1211 / 4333 27.948%
* interest 809 / 2368 34.163%
* lines 1417 / 4146 34.177%
* serve 832/ 4378 19.004%

### Varianta cu window = 7 si noile perechi de relatii

* hard  1292 / 4333 29.817%
* interest 843 / 2368 35.599%
* lines 1485 / 4146 35.817%
* serve 854/ 4378 19.506%