Download Link: https://assignmentchef.com/product/solved-605-201-introduction-to-programming-using-java-assignment-5
<br>
Morse code, developed in 1832 by Samuel Morse, is one of the most famous of all coding schemes ever developed. Morse code assigns a series of dots and dashes to each letter of the alphabet, each digit, and a few other punctuation characters. The international version of Morse code for alphabetic characters and digits is shown in the table below.




<table width="591">

 <tbody>

  <tr>

   <td width="148"><strong>Character</strong></td>

   <td width="56"> </td>

   <td width="92"><strong>code</strong></td>

   <td width="148"><strong>Character</strong></td>

   <td width="52"> </td>

   <td width="96"><strong>code</strong></td>

  </tr>

  <tr>

   <td width="148">A</td>

   <td width="56"><strong>.-</strong></td>

   <td width="92"> </td>

   <td width="148">T</td>

   <td width="52"><strong>–</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">B</td>

   <td width="56"><strong>-…</strong></td>

   <td width="92"> </td>

   <td width="148">U</td>

   <td width="52"><strong>..-</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">C</td>

   <td width="56"><strong>-.-.</strong></td>

   <td width="92"> </td>

   <td width="148">V</td>

   <td width="52"><strong>…-</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">D</td>

   <td width="56"><strong>-..</strong></td>

   <td width="92"> </td>

   <td width="148">W</td>

   <td width="52"><strong>.–</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">E</td>

   <td width="56"><strong>.</strong></td>

   <td width="92"> </td>

   <td width="148">X</td>

   <td width="52"><strong>-..-</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">F</td>

   <td width="56"><strong>..-.</strong></td>

   <td width="92"> </td>

   <td width="148">Y</td>

   <td width="52"><strong>-.–</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">G</td>

   <td width="56"><strong>–.</strong></td>

   <td width="92"> </td>

   <td width="148">Z</td>

   <td width="52"><strong>–..</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">H</td>

   <td width="56"><strong>….</strong></td>

   <td width="92"> </td>

   <td width="148"> </td>

   <td width="52"> </td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">I</td>

   <td width="56"><strong>..</strong></td>

   <td width="92"> </td>

   <td width="148">Digits</td>

   <td width="52"> </td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">J</td>

   <td width="56"><strong>.—</strong></td>

   <td width="92"> </td>

   <td width="148">1</td>

   <td width="52"><strong>.—-</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">K</td>

   <td width="56"><strong>-.-</strong></td>

   <td width="92"> </td>

   <td width="148">2</td>

   <td width="52"><strong>..—</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">L</td>

   <td width="56"><strong>.-..</strong></td>

   <td width="92"> </td>

   <td width="148">3</td>

   <td width="52"><strong>…–</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">M</td>

   <td width="56"><strong>—</strong></td>

   <td width="92"> </td>

   <td width="148">4</td>

   <td width="52"><strong>….-</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">N</td>

   <td width="56"><strong>-.</strong></td>

   <td width="92"> </td>

   <td width="148">5</td>

   <td width="52"><strong>…..</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">O</td>

   <td width="56"><strong>—</strong></td>

   <td width="92"> </td>

   <td width="148">6</td>

   <td width="52"><strong>-….</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">P</td>

   <td width="56"><strong>.–.</strong></td>

   <td width="92"> </td>

   <td width="148">7</td>

   <td width="52"><strong>–…</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">Q</td>

   <td width="56"><strong>–.-</strong></td>

   <td width="92"> </td>

   <td width="148">8</td>

   <td width="52"><strong>—..</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">R</td>

   <td width="56"><strong>.-.</strong></td>

   <td width="92"> </td>

   <td width="148">9</td>

   <td width="52"><strong>—-.</strong></td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="148">S</td>

   <td width="56"><strong>…</strong></td>

   <td width="92"> </td>

   <td width="148">0</td>

   <td width="52"><strong>—–</strong></td>

   <td width="96"> </td>

  </tr>

 </tbody>

</table>







This project involves writing a program to translate Morse code into English and English into Morse code. Your program shall prompt the user to specify the desired type of translation, input a string of Morse code characters or English characters, then display the translated results.  The Morse code pattern and English letter translations must be kept and processed using either two one-dimensional or one two-dimensional arrays.




When you input Morse code, separate each letter/digit with a single space, and delimit multiple words with a “|”. For example, <strong>– — | -… . </strong>would be the Morse code input for the sentence “to be”. Your program only needs to handle a single sentence and can ignore punctuation symbols.




When you input English, separate each word with a blank space.

<sup>         </sup>Be sure to comment your code anduse good programming style.




Submit the source code and  screen shots of each program’s output in a zip file named as follows: Assignment5 followed by an underscore (_) followed by your first name initial, followed by your last name, followed by your course section number. For example, if your name is Jane Smith and you are in section 81 your zip file would be <em>Assignment5_jsmith81.zip</em>.