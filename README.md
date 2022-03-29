**This shiny App is based on R-language, the version is R4.0.2**

## update
- \[tab/server/plot.R] : file changed -> If there is no group column, print the error message (10/18/2021 - YH)

## About R
- R 4.0.2  [download](https://cran.r-project.org/bin/windows/base/old/4.0.2/) (The latest version [download](https://cran.r-project.org/bin/windows/base/))
- After installing the R, download R studio and create R environment.
  -  R studio Desktop Open Source License [download](https://www.rstudio.com/products/rstudio/download/#download)
  
## How to run
1. From the code download button(green button), ![image](https://user-images.githubusercontent.com/77769026/125890089-b55dd5a4-0774-4517-b751-9c7915ca1439.png)store the zip file and unzip it to the desired location.

2. Run the script 'runApp.R' in the 'R-Shiny-IMa3_dashboard' folder.</br>
  2-1 If you run the code runnApp for the first time, run all the code. </br>
  2-2 If you have executed the code or if you have a mini-conda installed, It is recommended not to execute the "### install.packages ###" and "### Miniconda ###" codes.(But run the "### library packages ###" code.)</br>
  Especially, Miniconda code takes long time, and return the error (It's normal error, please ignore and run the next code!)

3. In runApp.R file, Change the working directory to R-Shiny-IMa3_dashboard by using the function setwd()
   ```r
   # example code 1
   setwd("C:/Users/rhtn2/OneDrive/Documents//R-Shiny-IMa3_dashboard")
   ```
   or
   ```r
   # example code 2
   setwd("C:/Users/Administrator/Desktop/R-Shiny-IMa3_dashboard")
   ```
 4. Run the whole code runApp.R script. (The dashboard will open at new brows)

 ** When you want to use the _Brun & Thin_ page, Please click the *'open in Browser'* button![image](https://user-images.githubusercontent.com/77769026/125890534-901ed15a-85c3-46b7-927c-2025a27ee15a.png) so that load a IMa3 output file.  **


## About Dashboard

### 1. Home
The first time you launch the browser, you will see the following screen.
![home_adj](https://user-images.githubusercontent.com/50395914/159407628-519c41f8-e3dd-4d94-a521-6c51958c48e2.png)


### 2. PLOT
This tab makes Histogram from IMa3's output</br>
Also, You can save the histogram in png, jpeg, pdf format
![plot](https://user-images.githubusercontent.com/50395914/159407352-b63dce4e-a34a-4951-919b-dce45ea40d1f.gif)


### 3. Brun & Thin
This tab takes a procedures for Burn-in and Thining from IMa3's output data.</br>
The output file will be saved in the same directory as input data.</br>
\<Example\> Burn-in : 10 , Thining : 10 -> The file name is 'b10t10.ti'
![bt](https://user-images.githubusercontent.com/50395914/159407372-e59e109c-85d8-4b9b-8dd2-379bb608c837.gif)

