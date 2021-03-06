# email-template
Sending emails to customers or leads is essential to the growth of your business. Although many email marketing platforms provide drag and drop email builders, they are confined to cookie cutter themes. This article provides you with an HTML email template you can customize to meet the needs of your business.

## Tutorial

For detailed instructions, view Solodev's [Crafting an HTML Email Template](https://www.solodev.com/blog/web-design/crafting-an-html-email-template.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/cfeh3crr/).

## HTML

The email template contains the following HTML markup.
```
<center>
<table align="center" border="0" cellpadding="0" cellspacing="0" height="100%" id="bodyTable" width="100%">
   <tbody>
      <tr>
         <td align="center" id="bodyCell" valign="top"><!-- BEGIN TEMPLATE // -->
         <div class="__ma__postal_address">&nbsp;</div>

         <table border="0" cellpadding="0" cellspacing="0" id="templateContainer">
            <tbody>
               <tr>
                  <td align="center" valign="top"><!-- BEGIN BODY // -->
                  <table bgcolor="#ebebeb" border="0" cellpadding="0" cellspacing="0" class="ct-container" style="margin: auto; background-color:#000;" width="100%">
                     <tbody>
                        <tr>
                           <td>
                           <table border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse;" width="100%">
                              <tbody>
                                 <tr>
                                    <td bgcolor="#000000" height="40">
                                    <table border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse;" width="100%">
                                       <tbody>
                                          <tr>
                                             <td width="15">&nbsp;</td>
                                             <td>
                                             <table border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse;" width="100%">
                                                <tbody>
                                                   <tr>
                                                      <td mc:edit="logo" style="padding-right:10px;"><a href="http://www.solodev.com/" target="_blank"><img alt="WebCorpCo Logo" src="images/logo-1.png" style="width:80%;" /></a></td>
                                                      <td align="right">
                                                      <table align="center" bgcolor="#000000" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse;">
                                                         <tbody>
                                                            <tr>
                                                               <td bgcolor="#000000" class="mobileHide" mc:edit="phone" style="font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#ffffff; padding-left:5px;  background-color: #000000;text-align: right;" width="188"><a href="tel:5555555555" style="color:#ffffff; text-decoration:none;">555.555.5555</a></td>
                                                            </tr>
                                                         </tbody>
                                                      </table>
                                                      </td>
                                                   </tr>
                                                </tbody>
                                             </table>
                                             </td>
                                             <td width="15">&nbsp;</td>
                                          </tr>
                                       </tbody>
                                    </table>
                                    </td>
                                 </tr>
                              </tbody>
                           </table>

                           <table border="0" cellpadding="0" cellspacing="0" id="templateBody" width="100%">
                              <tbody>
                                 <tr>
                                    <td class="bodyContent" mc:edit="body_content00" valign="top">
                                    <h1 style="color:#eb2123; font-size:40px;font-weight:bold;">Larger than Life Insights!</h1>

                                    <h3 style="font-size:20px;color:#000000;font-weight:bold;">Leverage the power of Big Data with WebCorpCo</h3>
                                    </td>
                                 </tr>
                                 <tr>
                                    <td class="bodyContent" style="padding-top:0; padding-bottom:0;"><a href="https://pv.webbyawards.com/2016/websites/general-website/associations" target="_blank"><img id="bodyImage" mc:allowtext="" mc:edit="body_image" mc:label="body_image" src="images/7critical.jpg"  /></a></td>
                                 </tr>
                                 <tr>
                                    <td class="bodyContent" mc:edit="body_content01" valign="top">
                                    <p>Thank you for requesting our case study on how WebCorpCo uses its own Big Data products to leverage business intelligence. You are the 1,000,0721th person to read it! Congrats!</p>

                                    <p>The most brilliant minds in Big Data, Data Mining, Pattern Analysis, Natural Language Processing, Recommender Systems, and Business Intelligence collaborated to bring you this report! Here it is, in all its glory!</p>

                                    <p>We hope you enjoy the lessons to be gleaned from our case study and look forward to working with you hand in hand to bring business intelligence to the fold for your organization!</p>
                                    </td>
                                 </tr>
                                 <tr>
                                    <td height="14" style="padding:18px 40px; width:200px">
                                    <p style="text-align: center;"><a href="https://pv.webbyawards.com/2016/websites/general-website/associations" mc:edit="button" target="_blank"><img src="images/learn.jpg" /></a></p>
                                    <br />
                                    &nbsp;</td>
                                 </tr>
                              </tbody>
                           </table>
                           </td>
                        </tr>
                     </tbody>
                  </table>
                  <!-- // END BODY --></td>
               </tr>
               <tr>
                  <td align="center" valign="top"><!-- BEGIN FOOTER // -->
                  <div mc:edit="socialicons" style="text-align: center;background-color: #000;padding-top: 40px;"><br />
                  <a href="" style="border:none;" target="_blank" title="Facebook"><img alt="Facebook" src="images/facebook-email-icon-1.png" /></a> <a href="" style="border:none;" target="_blank" title="Twitter"> <img alt="Twitter" src="images/twitter-email-icon-1.png" /></a> <a href="" style="border:none;" target="_blank" title="Linkedin"> <img alt="Linkedin" src="images/linkedin-email-icon-1.png" /> </a></div>

                  <div mc:edit="footertext" style="text-align: center;background-color: #000;font-size:13px; padding-bottom: 40px;padding-top: 10px;padding-left:10px;padding-right:10px;color: #fff;">
                  <p><a href="" style="color: #eb2123;font-weight:bold;margin-bottom:10px;text-decoration:none;font-family:arial,sans-serif;" target="_blank">WebCorpCo</a></p>

                  <p><a href="https://www.google.com/maps/place/999+18th+St+%233000,+Denver+Place,+Denver,+CO+80202/data=!4m2!3m1!1s0x876c78da287122a9:0x1f7a76af26546f63?sa=X&amp;ved=0ahUKEwj2uees_47MAhUFPCYKHZw3AOMQ8gEIHDAA" style="color: #fff;margin-bottom:10px;text-decoration:none;font-family:arial,sans-serif;" target="_blank">123 Easy Street | Orlando, Florida 32803</a></p>

                  <p style="color: #fff;margin-bottom:10px;text-decoration:none;font-family:arial,sans-serif;"><a href="tel:8889605299" style="color: #fff;margin-bottom:10px;text-decoration:none;font-family:arial,sans-serif;">Phone: 555.555.5555 </a></p>

                  <p style="color:#fff !important;font-family:arial,sans-serif;"><br />
                  Don&rsquo;t want to receive email Updates? <a href="{MA_UNSUBSCRIBE}" style="color:#eb2123 !important;font-family:arial,sans-serif;">Unsubscribe here</a><br />
                  <br />
                  &copy; 2016 WebCorpCo. All rights reserved.<br />
                  <br />
                  &nbsp;</p>
                  </div>
                  <!-- // END FOOTER --></td>
               </tr>
            </tbody>
         </table>
         <!-- // END TEMPLATE --></td>
      </tr>
   </tbody>
</table>
</center>
```
## CSS

All necessary CSS is in email.css
