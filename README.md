# git_assignment_HeroVired
# Calculatorplus application
The application provides basic arithmetic operations, such as addition, subtraction, multiplication, division, and also the square root of the numbers.

# Geometry Calculator
Contains a simple Python program that calculates the area of a circle and the area of a rectangle

# LFS
That LFS branch contains a large binary file with 200MB, let's follow the steps mentioned below to upload large files in your git repo using lfs.
* First install LFS --> " git lfs install "
* Then track your file using lfs track command ' git track lfs "*.bin" ' , here '.bin' represents the file extension.
* you can able to see gitattributes text file created with tracked details " *.bin filter=lfs diff=lfs merge=lfs -text " like this.
* Follow the regular sequence command to push the file into your repo.
   git lfs push --all origin LFS
   git add .
   git commit -m "commit message"
   git push -u origin LFS
