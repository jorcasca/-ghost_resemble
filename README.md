# Resemble testing in web app

## Requirement

*  [Ghost installed and running](https://ghost.org/docs/install/local/)
*  [ResembleJS](https://rsmbl.github.io/Resemble.js/)

### NOTE: Ghost needs to be installed from scratch.
The new version used was Ghost version: 5.23.0 and old version was 3.42.

## Steps to run the test

1. Go to the Ghost-Resemble folder.
3. Execute tests
    ```sh        
    npm install
    node index.js
    ```
4. Watch regression test running.

## Results

Inside the result folder are the feature folders. Inside each one you will find folders with the format E<scenario> where scenario corresponds to the scenario number. Finally, within each one you will find the comparison screenshots and the corresponding report. 

### Ex.
![image](https://user-images.githubusercontent.com/31069035/202922305-78746b63-e279-49d1-97ff-434380b4f688.png)
