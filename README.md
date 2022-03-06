# latexchat

## How to
### 1. Install a latex compiler, such as https://miktex.org/download.
### 2. Install a latex editor, such as https://www.xm1math.net/texmaker.
### 3. Open the chat.tex, replace the text within ```\begin{chat}``` and ```\end{chat}```.
#### 3.1 A blank line will change the side of the bubble.
#### 3.2 A text line finished with \\ will keep it in the same bubble as the previous line.
#### 3.3 In order to change the page height, use the following parameter in the 4th line: paperheight=18in
#### 3.4 Add or remove pictires from the list \def\names{{image1.png},{image2.png}} 
### 4. Compile it.

## In case you need apply transformations to the whole text, try regex.
### Some examples here:
#### Adding new line and spaces: https://regexr.com/6g9lm
#### Removing special characters
#### Adding double back slashes to the end of the lines
