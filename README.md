 <html>
    <head>
        <title>form page</title>
    </head>
    <CENTER>
    <table BORDER="2PX"bGcolor="SKYBLUE" bordercolor="yellow"cellspacing="0px">
        <form>
            <DIV style="background-color: YELLOW;font-size:30PX;COLOR:RED;font-weight:bold;width: 500PX;"><marquee direction="right" scrollamount="20"behaviour="alternate">REGISTRATION FORM</marquee></DIV>
            <body topmargin="100"bGcolor="CYAN">

                <tr>
                    <td>NAME</td>
                    <td><input type="text" required></td></tr>
                    <tr>
                        <td>ROLL NO</td>
                        <TD><INPUT TYPE="TEXT" required></TD>
                    </tr>
                    <TR>
                        <TD>E-MAIL</TD>
                        <TD><INPUT TYPE="email" required></TD>
                    </TR>
                    <TR>
                        <TD>GENDER</TD>
                        <TD><INPUT TYPE="RADIO"NAME="TYPE" required>MALE
                            <INPUT type="RADIO"NAME="TYPE" required>FEMALE</TD>
                    </TR>
                    <TR>
                        <TD>CONTACT NO</TD>
                        <TD><select>
                            <OPTION>+91</OPTION>
                            <option>+82</option>
                            <option>+83</option>
                             <OPTION>+84</OPTION>
                             <OPTION>+85</OPTION>
                             <OPTION>+86</OPTION>
                             <OPTION>+90</OPTION>
                             <OPTION>+91</OPTION>
                             <OPTION>+92</OPTION>
                             <option>+93</option>
                        </select>
                            <INPUT TYPE="NUMBER"required></TD>
                    </TR>
                    <TR>
                        <TD>SELECT YOUR HOBBIES</TD>
                            <TD><INPUT TYPE="checkbox">SPORTS
                                <INPUT TYPE="checkbox">MUSIC
                                    <INPUT TYPE="checkbox">DANCE
                                        <INPUT TYPE="checkbox">GAME</TD>
                        </TD>
                    </TR>
                    <TR>
                        <TD>SELECT YOUR PHOTO</TD>
                        <TD><INPUT type="FILE"NAME="FILENAME" id="MYFILE"></TD>
                    </TR><td>

                    <TR>
                        <TD colspan="2"ALIGN="CENTER"height="50PX"bGcolor="GRAY">
                            <INPUT TYPE="button"VALUE="CANCEL">
                                <input TYPE="SUBMIT"></TD></TR>
                </CENTER>

            </body>
        </form>
    </table>
</html>
