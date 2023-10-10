# randomInputsPhysicsExams
This repo contains a database of Physics exercises for generating exams with random inputs. For that, I use a R library (Sweave), which permits building **LaTeX** documents with chunks of **R**.

This is awesome, since, this way, you can create documents using logic on the background!

With this logic, as I make here, you can not only generate random inputs, but also build the logic to create both correct and false answers.

Besides, you can expand Latex functionality to create both the documents (an exam in this case) and the proof with the solutions printed on it, very useful for fast corrections.

# Cloning 
You can clone this repository by open a terminal an typing
```shell
git clone https://github.com/BorjaRuizReverter/randomInputsPhysicsExams.git
```
For that, make sure that you have installed the [Git](https://git-scm.com/downloads) tool.

Then navigate to the new folder that the clone tool created:
```shell
cd randomInputsPhysicsExams
```

# Installing
For building your random pdf exam you must install the software required firstly. You will need:
1. The R compiler, which you can download it from the official [website](https://cran.r-project.org/mirrors.html).
2. An R IDE like RStudio, which you can download it from the official [website](https://www.rstudio.com/products/rstudio/download/).
3. A Latex compiler like MiKTeX, recommended for Windows users, which you can download it from [here](https://miktex.org/download), or LiveTex, recommended for Linux users, which you can download it from [here](https://tug.org/texlive/acquire-netinstall.html).

# Compiling
Once you have all installed, open the Rnw file from Rstudio and finally compile the pdf.

# Example
This below is an exam example. Note that all numbers are randomly generated and every solution matches those random inputs.

<img src="/assets/Prova_finalA_pag1.pdf"/>