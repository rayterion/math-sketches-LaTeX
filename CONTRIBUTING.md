# Setting up the development environment

## Windows

1. install [MikTeX](https://miktex.org/)
2. install the VSCode Extension [LaTeX Workshop extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
3. install [Strawberry Perl](https://strawberryperl.com/)

# How to check it's working

1. Open the LaTeX workshop extension in VSCode within the project folder.
2. Open the `main.tex` file and click on the "Build LaTeX project" button in the top right corner of the editor.
3. If everything is set up correctly, the build process should start and you should see the output in the terminal. If there are any errors, they will be displayed in the terminal as well.
4. Once the build process is complete, you should see a PDF file generated in the same directory as the `main.tex` file. You can open this PDF file to verify that it was generated correctly.
5. Then, also in the LaTeX workshop extension, click on the "View LaTeX PDF" button to open the generated PDF file within VSCode. This will allow you to see the output of your LaTeX code directly in the editor.

# How ot contribute

Once the setup is done, you can create any .tex file in the folders you find the most relevant to your idea.
For example, i've added a file called `boulos-resol.tex` in the `analytical-geometry` folder, which contains a sketch of the solution to the problem of Apollonius using only analytical geometry and algebraic manipulation.

Feel free to create your own folders with your tex files.

*Note:* For the pdf view to work, you must update main.tex with the file you created.