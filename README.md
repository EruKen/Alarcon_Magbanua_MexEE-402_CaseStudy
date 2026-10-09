<h2 align="center"><b>MexEE 402: Data Preprocessing Case Study</b></h2>
<h3 align="center"><b>MexEE Elective 2: Data Science and Machine Learning</b></h2>
<h3 align="center"><b>Batangas State University, Alangilan Campus</b></h3>
<h3 align="center"><b>1st Semester, AY 2026-2027</b></h3>

<br>

## Members
<table align="center">
  <tr>
    <th>Name</th>
    <th>Student Number</th>
    <th>Section</th>
  </tr>
  <tr>
    <td>Alarcon, John Lee Keneth</td>
    <td>23-03487</td>
    <td>MEXE - 4101</td>
  </tr>
  <tr>
    <td>Magbanua, Yna Bianca</td>
    <td>23-02697</td>
    <td>MEXE - 4101</td>
  </tr>
</table>

</div>

<br>

## Notebook links
<div align="center">

<p><strong>The seven notebooks:</strong></p>

<table align="center">
  <tr>
    <th>Notebook</th>
    <th>Topic</th>
  </tr>
  <tr>
    <td align="center">Ch1_2_3</td>
    <td align="center">Introduction to preprocessing, exploring and cleaning data</td>
  </tr>
  <tr>
    <td align="center">Ch4</td>
    <td align="center">Transformation, feature engineering, and encoding</td>
  </tr>
  <tr>
    <td align="center">Ch5</td>
    <td align="center">Scaling and normalization</td>
  </tr>
  <tr>
    <td align="center">Ch6</td>
    <td align="center">Outlier detection</td>
  </tr>
  <tr>
    <td align="center">Ch7</td>
    <td align="center">Feature selection</td>
  </tr>
  <tr>
    <td align="center">Ch8</td>
    <td align="center">Constructing a preprocessing pipeline</td>
  </tr>
  <tr>
    <td align="center">Ch9</td>
    <td align="center">Full pipeline and visualization</td>
  </tr>
</table>

</div>

<br>

<div align="center">

<table>
  <tr>
    <th>Chapter</th>
    <th>Alarcon, John Lee Keneth</th>
    <th>Magbanua, Yna Bianca</th>
  </tr>
  <tr>
    <td>Ch1_2_3</td>
    <td><a href="https://colab.research.google.com/github/MikkoDT/MexEE402_AI/blob/main/Blank_Ch1_2_3.ipynb">Chapter1-3</a></td>
    <td><a href="https://colab.research.google.com/drive/12Tl-kVLfnLyNxWXVYf8Pkp4C5mvknpPO?usp=drive_link">Chapter 1-3</a></td>
  </tr>
  <tr>
    <td>Ch4</td>
    <td><a href="">link</a></td>
    <td><a href="">https://colab.research.google.com/drive/1xWBBHXMZY97VFlOyZdTz2htUZDKfkJDD?usp=drive_link</a></td>
  </tr>
  <tr>
    <td>Ch5</td>
    <td><a href="">link</a></td>
    <td><a href="">https://colab.research.google.com/drive/1OFgqqMwe1aL9eVkynsAkX22UPeyDyzyA?usp=drive_link</a></td>
  </tr>
  <tr>
    <td>Ch6</td>
    <td><a href="">link</a></td>
    <td><a href="">https://colab.research.google.com/drive/1D5k0W_E3BtYN-1JXuyMgUWdVrPLkdyLk?usp=drive_link</a></td>
  </tr>
  <tr>
    <td>Ch7</td>
    <td><a href="">link</a></td>
    <td><a href="">https://colab.research.google.com/drive/1GcXDFECf3Y0_c0gumCqOj83yjg0IHlnw?usp=drive_link</a></td>
  </tr>
  <tr>
    <td>Ch8</td>
    <td><a href="">link</a></td>
    <td><a href="">https://colab.research.google.com/drive/1kuMBOJ_hso0arVVRuIztaFdrF8sMhoP7?usp=drive_link</a></td>
  </tr>
  <tr>
    <td>Ch9</td>
    <td><a href="">link</a></td>
    <td><a href="">https://colab.research.google.com/drive/1EkMbCrr4IgvKapXhrrfg-ovF3J4ynqUm?usp=drive_link</a></td>
  </tr>
</table>

</div>

<br>

## What we learned

  When I started, I assumed data was ready to use the moment I opened it, but Chapter 1 hads taught me that raw data is often messy, with missing pieces and inconsistent details, and that it has to be checked and tidied before anyone can trust it. What surprised me most was that cleaning involves choices, not just rules. When we removed the biggest sellers as “outliers,” we also removed famous games, so I had to think about what I was really throwing away.

  Chapter 4 about Transformation and Feature Engineering, I learned that I can create new, useful information from what I already have. Dividing lemonade sold by temperature gave me a clearer picture than either one alone. What surprised me is that turning words into numbers needs care. If I labeled sunny, cloudy, and rainy as 1, 2, and 3, the computer would think rainy is “more” than sunny, even though they have no real order.

  I understood in Chapter 5: Scaling and Normalization, that a computer has no idea what numbers mean. It only sees their size, so a column with bigger numbers can seem more important even when it isn’t. What surprised me is that scaling doesn’t change the information at all. It only changes the measuring stick, so everything can be compared fairly.

  Chapter 6 about Dealing with Outliers I learned that an outlier is a value that doesn’t fit with the rest, and that there is more than one way to spot it. What surprised me most is that one method missed the value of 100 even though it clearly looked strange, while the other caught it right away. That showed me no single method is perfect, so it is smart to double-check.

  In Chapter 7, I learned that having more information is not always better, because unhelpful details can confuse the computer. What surprised me is that the three methods picked different answers from the same data. It taught me that tools don’t always agree, especially when there is very little data, so I shouldn’t treat one answer as the final truth.

  I Chapter 8, I was amazed that a pipeline works like a conveyor belt, the same steps happen in the same order every time. Order matters, because you have to fill in the gaps before you adjust the sizes. What surprised me is that once the steps are set up, they can be reused on new data, which saves time and avoids mistakes.

  The last Chapter about Real-World Application, showed me how everything from the earlier chapters fits together on one real story, the Titanic passengers. What surprised me is that preprocessing is never really “done.” I have to keep checking my work, and even a chart can be mislabeled or show something different from what I expected. Making charts helped me see patterns, but it also helped me double-check myself.
  
<br>

## Errors we found

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

<br>

## Note on AI tools

Yes, I used an AI tool, specifically Claude, while working on the chapter questions, but only for the parts I could not understand just by looking at the notebook. I chose Claude because it is better at coding and explaining code, which helped a lot since the notebooks were full of Python and library functions. When the notebook’s explanation and code output were enough, I answered on my own. I asked Claude to explain them in simpler words. I then compared its explanations with the notebook outputs, such as the missing value counts and the Z-score result, and wrote my final answers and reflections myself.

<br>

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
