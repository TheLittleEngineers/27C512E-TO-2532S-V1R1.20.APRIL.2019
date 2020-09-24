# 27C512E-TO-2532S-V1R1.20.APRIL.2019
TheLittleEngineers.org-27C512E-TO-2532S-V1R1.20.APRIL.2019
27C512 E.P.R.O.M. TO TMS2532 SOCKET CONVERTER.
(C) 20 April 2019 and 01 June 2019 by: Robert Allen Turner
http://www.TheLittleEngineers.org/
https://github.com/TheLittleEngineers

This product is intended to allow a 27512 or 27C512 EPROM to be placed into a TMS2532 EPROM socket. The 27512 is divided into 16 banks of 4Kbytes via the four jumpers at the bottom of the socket.

Released under a Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) License, 01 June 2019 In Memory of my Father, Robert Embry Turner, 1945 - 2019. Rest In Peace. I LOVE YOU DAD!

Archive name: "TheLittleEngineers.org-27C512E-TO-2532S-V1R1.20.APRIL.2019"

This is an update to the "TheLittleEngineers.org-27C512E-TO-2532S-V1R0.20.APRIL.2019" repository which resides at this url:
https://github.com/TheLittleEngineers/27C512E-TO-2532S-V1R0
This update was made due to the fact that I was not very pleased with the initial Printed Circuit Boards that resulted from the original design. Although functional, the production of the Printed Circuit Boards was inconsistent between different manufacturers. This was due to a problem in the dimension layer of the original design and so I have created this new design to eliminate the inconsistencies.

This version should provide much better results.

Please note: This is derived from an original design by "Little" John Eric and/or his father "Big" John Robert (J.R.) by "Uncle" Robert Allen. It should be thoroughly scrutinized and verified prior to actual use of any kind. DISCLAIMER: The following article is provided for informational purposes only. Any attempt to modify your computer without the proper skills to do so may void your computer. Any attempt to modify your computer without unplugging it first may void you. This Information is provided "as-is" with no guarantee of fitness for any purpose, either explicit or implied. We disclaim any and all responsibility for losses incurred through the use of this information. By using this information, you are deemed to have accepted these conditions of use, and you agree NOT to sue us. CLARIFICATION: The above disclaimer states as plainly as possible that if you decide to make use of any of the information contained within this document that you do so at your own risk. Designing hardware for the CoCo (ColorComputer) and other vintage hardware is a hobby of ours and is not motivated by any desire of profits. As this is a not for profit venture, obviously we can't afford not to disclaim the use of this information.

The GitHub home of this project is available at the following url:
https://github.com/TheLittleEngineers/27C512E-TO-2532S-V1R1.20.APRIL.2019

This design is available at OSHPark with the following urls:
https://oshpark.com/shared_projects/JmUiHyi1 (EAGLE .brd)
https://oshpark.com/shared_projects/4RvjjYdM (KiCAD .kicad_pcb)
Note that the KiCAD version has been imported using the EAGLE import function of the Version 5.x of KiCAD. As such, it may be potentially problematic.

<!DOCTYPE html>
<html>
<head>

<meta name="Author" content="Robert &quot;The R.A.T.&quot; Allen Turner">
<meta name="GENERATOR" content="Tandy Radio Shack TRS-80 Color Computer 3">
<meta name="ProgId" content="TeleWriter-128.by.Bob.Van.der.Poel.for.Cognitec">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="Content-Language" content="en-us">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!--
<!meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
This HTML is a veritable train wreck, however, it seems to get the job done on 24 September 2020 and beyond
-->



</head>

<body style="background-color:WhiteSmoke;">

<!-- Top Row -->
<center>
<h3 style="text-align: center; color: Black;">This page created: April 10, 2019, last updated: September 24, 2020, served: 
</center>
<p align="center">
<font size="6"><a href="http://www.TheLittleEngineers.org/" target="_blank">The</a> <a href="http://www.TheLittleEngineers.org/" target="_blank">Little</a> <a href="http://www.TheLittleEngineers.org/" target="_blank">Engineers</a> in conjunction with <a href="http://www.RetroATX.com" target="_blank">Retro</a><u>-</u><a href="http://www.Retro-ATX.com" target="_blank">ATX</a><br></font>
<font size="5"><em><b><a href="https://www.facebook.com/OurLittleEngineers/" target="_blank">Pulling</a> <a href="https://www.facebook.com/groups/985537051651794/" target="_blank">The</a> <a href="https://www.facebook.com/groups/566741160795144/" target="_blank">Past</a> <a href="https://www.facebook.com/TheLittleEngineers.org" target="_blank">Into</a> <a href="https://www.facebook.com/tincansandducttape/" target="_blank">The</a> <a href="https://www.facebook.com/Tin-Cans-Duct-Tape-728969003939754/" target="_blank">Present</a> <a href="https://www.facebook.com/groups/1654785514796788/" target="_blank">For</a> <a href="https://www.facebook.com/groups/1828354620822631/" target="_blank">The</a> <a href="https://www.facebook.com/groups/1451396811790867/" target="_blank">Future</a><a href="https://www.facebook.com/cpldfpga/" target="_blank"></a></b></em><br></font>
</p>
<p align="justify"><a href="http://www.TheLittleEngineers.org/" target="_blank">The</a> <a href="http://www.TheLittleEngineers.org/" target="_blank">Little</a> <a href="http://www.TheLittleEngineers.org/" target="_blank">Engineers</a> is a project began in 2011 by <a href="mailto:TheLittleEngineers@OutLook.com" target="_blank">Robert</a> <a href="mailto:LittleEngineer_RAT@OutLook.com" target="_blank">Allen</a> <a href="mailto:OurLittleEngineers@gMail.com" target="_blank">Turner</a> (hereafter, <a href="mailto:LittleEngineer.RAT@gMail.com" target="_blank">I</a>, <a href="mailto:TinCansAndDuctTape@gMail.com" target="_blank">Me</a>, <a href="mailto:CannedLogic@gMail.com" target="_blank">My</a>, <a href="mailto:TinCansAndDuctTape@OutLook.com" target="_blank">Author</a>, or <a href="mailto:LittleEngineer.RAT@OutLook.com" target="_blank">&quot;The R.A.T.&quot;</a>), for the benefit of foster children and their families (foster and biological). The original intent was simply to provide a means, in the form of donated cameras, of creating videos with the foster families such that the biological parents did not completely miss out on their children growing up. Providing simple to construct kits (electronics, arts, crafts, etcetera) seemed a logical choice as subject matter for such videos and these types of activities have the benefit of being educational. It is thus that those types of projects are primarily what <a href="mailto:LittleEngineer.RAT@OutLook.com" target="_blank">I</a> attempt to develop for use in such videos. This is a difficult, time consuming and expensive undertaking. Each case must be handled on an individual basis and any such videos and communications must be scrutinized and approved on a per case basis by the case workers, et alia in charge. Although this makes such an undertaking extremely difficult, it is a necessity in order to protect the children. Some are, after all, being protected from abusive family members and so there has to be a very strict set of protocols in place. This has prevented me from fully launching <a href="https://www.facebook.com/OurLittleEngineers/" target="_blank">The</a> <a href="https://www.facebook.com/groups/985537051651794/" target="_blank">Little</a> <a href="https://www.facebook.com/TheLittleEngineers.org" target="_blank">Engineers</a><a href="https://www.facebook.com/groups/566741160795144/" target="_blank"></a> over the past eight years, but I remain fully committed to the project with the intent of seeing it through to a fully operational entity.
</p>
<p align="justify"><a href="http://www.RetroATX.com" target="_blank">Retro</a><u>-</u><a href="http://www.Retro-ATX.com" target="_blank">ATX</a> was conceived with the sole purpose of creating &quot;ATX form factor&quot; versions of various <em>classic</em> and <i>vintage</i> computing and other systems. Such a system might be an Altair 8800 &quot;clone&quot; in an ATX or &micro;ATX form factor. Certainly, a system compatible with the Tandy Radio Shack TRS-80 Model II, 12, 16 and 6000 line of computers is planned, as are ATX or &micro;ATX versions of the following systems:<ul align="justify"><li align="justify">Sinclair QL</li><li align="justify">Dragon D64 and D200</li><li align="justify">Dragon Alpha</li><li align="justify">Dragon Beta</li><li align="justify">Tandy Color Computer 3</li><li align="justify">Mattel Intellivision &quot;Keyboard Component&quot;</li><li align="justify">Aamber Pegasys</li><li align="justify">MicroBox ][</li><li align="justify">Various Frank Hogg Laboratories Systems, including:<ul align="justify"><li align="justify">FHL &quot;K-Buss&quot; backplanes of many sizes and configurations</li><li align="justify">FHL Tomcat Series, including:<ul align="justify"><li align="justify">FHL TC-9 6809 CPU board</li><li align="justify">FHL TC-9 I/O board</li><li align="justify">FHL TC-70 68070 CPU board</li><li align="justify">FHL TC-70 I/O and all other boards</li></ul></li></ul></li><li align="justify">GIMIX 6800/6809 Series Motherboards</li><li align="justify">GIMIX 6800/6809 Series CPU boards</li><li align="justify">GIMIX 6800/6809 Series Peripheral Cards</li><li align="justify">SWTPC 6800/6809 Series Motherboards</li><li align="justify">SWTPC 6800/6809 Series CPU boards</li><li align="justify">SWTPC 6800/6809 Series Peripheral Cards</li></ul>
</p>
<p align="justify">The above list represents just some of the systems that are planned for reimplementation by <a href="http://www.RetroATX.com" target="_blank">Retro</a><u>-</u><a href="http://www.Retro-ATX.com" target="_blank">ATX</a>. Any suggestions for other systems and features are welcomed. The MicroBox ][, Aamber Pegasus and Frank Hogg Laboratory systems are a priority at present, although this may change based upon feedback received. Undertaking any one of the above projects is a monumental task, requiring the expenditure of many hours of work and yet we fully intend to complete each and every one of those projects as time and resources allow. It is very unlikely that we will be able to complete all of these projects without the assistance of the many members of the <em>&quot;Vintage Computing Community&quot;.</em> We are in dire need of donations of any of the following items:<ul align="justify"><li align="justify">SCHEMATICS, documentations, Theory of Operations, etcetera of any and all of the above listed equipment</li><li align="justify">Any of the above hardware and peripherals that you may no longer have need of, functional or not</li><li align="justify">Your expertise, experience, opinions, engineering and other skills, etcetera</li></ul><b>Any items of interest, from the above list(s) or otherwise may be delivered to:</b>
</p>
<p align="center"><b>The Little Engineers Project/RetroATX.com<br>C/O Robert Turner<br>69 Lilly Lane<br>Pell City, AL 35125</b></p>
<p align="justify">Your continued encouragement and <a href="#support">support</a> are greatly appreciated. Other methods of <a href="#digitalcurrency">potential</a> <a href="#patreon">support</a> are contained <a href="#support">further</a> into this <a href="#support">document</a>. Thank You and God Bless.</p>
 
<p align="justify"><b>The logos, names and other material relating to <a href="https://www.facebook.com/OurLittleEngineers/" target="_blank">The</a> <a href="https://www.facebook.com/groups/985537051651794/" target="_blank">Little</a> <a href="https://www.facebook.com/TheLittleEngineers.org" target="_blank">Engineers</a><a href="https://www.facebook.com/groups/566741160795144/" target="_blank"></a>, <a href="http://www.TheLittleEngineers.org/" target="_blank">TheLittleEngineers.org</a>, <a href="http://www.RoboCircuits.org/" target="_blank">RoboCircuits</a>, <a href="http://www.RoboCircuits.org/" target="_blank">RoboCircuits.org</a>, <a href="https://www.facebook.com/tincansandducttape/" target="_blank">Tin</a> <a href="https://www.facebook.com/groups/1654785514796788/" target="_blank">Cans</a> <a href="https://www.facebook.com/Tin-Cans-Duct-Tape-728969003939754/" target="_blank">And</a> <a href="https://www.facebook.com/groups/1828354620822631/" target="_blank">Duct</a> <a href="https://www.facebook.com/groups/228910954180459/" target="_blank">Tape</a>, <a href="http://www.tincansandducttape.com/" target="_blank">TinCansAndDuctTape.com</a>, <a href="http://www.tcadt.com/" target="_blank">TCADT</a>, <a href="http://www.tcadt.com/" target="_blank">TCADT.com</a>, <a href="http://www.CannedLogic.com/" target="_blank">Canned Logic</a>, <a href="http://www.CannedLogic.com/" target="_blank">CannedLogic.com</a>, <a href="http://www.RetroATX.com/" target="_blank">RetroATX</a>, <a href="http://www.RetroATX.com/" target="_blank">RetroATX.com</a>, <a href="http://www.Retro-ATX.com/" target="_blank">Retro-ATX</a>, <a href="http://www.Retro-ATX.com/" target="_blank">Retro-ATX.com</a>, <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Zombie</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Software</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Systems</a>, <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/BinarySystems" target="_blank">Binary</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/BinarySystems" target="_blank">Systems</a>, <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip</a> and <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> are the sole property of <a href="https://www.facebook.com/TheLittleEngineers.org" target="_blank">Robert</a> <a href="mailto:TheLittleEngineers@OutLook.com" target="_blank">Allen</a> <a href="https://www.facebook.com/TinCansDuctTape" target="_blank">Turner</a> with <em>All Rights Reserved</em>.</b> The rights to the <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> domain and <a href="https://www.github.com/TheLittleEngineers?tab=repositories" target="_blank">products</a> were acquired by the <a href="https://www.facebook.com/TheLittleEngineers.org" target="_blank">author</a> on 25 December 2018 from my brother and his son, the former owners/operators of <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a>. Please note that the author is unable to answer any inquiries, including those of support or otherwise, in relation to <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> prior to his acquisition of same on 25 December 2018. This is primarily because the author posseses no knowlege of the site operation prior to that time. Although I have been provided with a large number of files that were originally contained on the website, it is unlikely that I will resurrect <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> other than perhaps as a <a href="http://www.TheLittleEngineers.org/WebSites/GIMEchip/" target="_blank">page</a> on <a href="http://www.TheLittleEngineers.org/WebSites/GIMEchip/" target="_blank">one</a> of my other websites. These files are mostly HTML page files and C.A.D. files of the products designed and developed by my nephew and his father, and very little else. As part of the acquisition agreement, all products previously produced by <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> are to be released under a <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License, as time and resources permit. Although many of these projects are somewhat interesting, none of them seem particularly useful or revolutionary.</p>
<p align="center">
<font size="6">DISCLAIMER:<br></font>
<font size="5"><em>Please Read Carefully.<br></em></font>
</p>
<p align="justify">This information is provided for informational purposes only. Any attempt to modify your equipment (including, but not limited to kit assembly) without the proper skills to do so may void your equipment. Any attempt to modify your equipment without unplugging it first may void you. This Information is provided "as-is" with no guarantee of fitness for any purpose, either explicit or implied. We disclaim any and all responsibility for losses incurred through the use of this information. Included with this information may be one or more C.A.D. Libraries, such as for E.A.G.L.E., KiCAD, etcetera. Any such C.A.D. libraries, except as may be noted are released under a <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License. You may use these libraries in your own projects, however, please take note that we CANNOT guarantee the accuracy of the components (nor any part of these libraries and/or information). We make NO guarantees that the components, footprints or schematic symbols contained in these libraries are flawless, and we make no promises of fitness for production, prototyping or any other purpose. These libraries and/or information are provided for informational purposes only, and are used at your own discretion. By downloading these libraries and/or information, you agree that we cannot be held responsible for faulty PCBs (Printed Circuit Boards). <b>You should always check the footprints with a 1:1 printout.</b> Neither Robert Allen Turner, <a href="https://www.facebook.com/OurLittleEngineers/" target="_blank">The</a> <a href="https://www.facebook.com/groups/985537051651794/" target="_blank">Little</a> <a href="https://www.facebook.com/TheLittleEngineers.org" target="_blank">Engineers</a><a href="https://www.facebook.com/groups/566741160795144/" target="_blank"></a>, <a href="http://www.TheLittleEngineers.org/" target="_blank">TheLittleEngineers.org</a>, <a href="https://www.facebook.com/tincansandducttape/" target="_blank">Tin</a> <a href="https://www.facebook.com/groups/1654785514796788/" target="_blank">Cans</a> <a href="https://www.facebook.com/Tin-Cans-Duct-Tape-728969003939754/" target="_blank">And</a> <a href="https://www.facebook.com/groups/1828354620822631/" target="_blank">Duct</a> <a href="https://www.facebook.com/groups/228910954180459/" target="_blank">Tape</a>, <a href="http://www.tincansandducttape.com/" target="_blank">TinCansAndDuctTape.com</a>, <a href="http://www.tcadt.com/" target="_blank">TCADT</a>, <a href="http://www.tcadt.com/" target="_blank">TCADT.com</a>, <a href="http://www.CannedLogic.com/" target="_blank">Canned Logic</a>, <a href="http://www.CannedLogic.com/" target="_blank">CannedLogic.com</a>, <a href="http://www.RetroATX.com/" target="_blank">RetroATX</a>, <a href="http://www.RetroATX.com/" target="_blank">RetroATX.com</a>, <a href="http://www.Retro-ATX.com/" target="_blank">Retro-ATX</a>, <a href="http://www.Retro-ATX.com/" target="_blank">Retro-ATX.com</a>, <a href="http://www.RoboCircuits.org/" target="_blank">RoboCircuits</a>, <a href="http://www.RoboCircuits.org/" target="_blank">RoboCircuits.org</a>, <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Zombie</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Software</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Systems</a>, <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/BinarySystems" target="_blank">Binary</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/BinarySystems" target="_blank">Systems</a>, <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip</a>, <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a>, nor anyone affiliated with same shall be held responsible for any outcome resulting from the usage of these files and/or information. Should any errors be found, please contact us at one of the provided email addresses and we will attempt to repair them. Unless otherwise noted, content of this library and other information is licensed under a <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License, <b><em>in memory of my Father</em>, <i>Robert Embry Turner</i>, 1945-2019 - I LOVE AND MISS YOU DAD! <em>Rest In Peace</em></b>. By using this information, you are deemed to have accepted these terms and conditions of use, and you agree NOT to sue us.</p>
<p align="center"><font size="5"><em>CLARIFICATION:</em></font></p>
<p align="justify">The disclaimer states as plainly as possible that if you decide to make use of any of the information contained within this document and/or any of the accompanying files that you do so at your own risk. Designing products for the <a href="http://www.TheLittleEngineers.org/" target="_blank">Little Engineers Project</a> and/or affiliates is not motivated by any desire of profits. As this is a not for profit venture, obviously we can't afford not to disclaim the use of this information. Thank You for your understanding and acceptance of these terms of use.</p>
<hr>
<!-- /Top Row -->

<!-- Top Left Column -->
<div class="row" style="background-color:WhiteSmoke;" align="center">
<div class="column" style="background-color:WhiteSmoke;" align="center">
<h2 align="center"><a href="http://www.TheLittleEngineers.org/pages/reference/20200103/IMDb/WhoAmI.htm" target="_blank">Who Am I?</a><br>Hint: I'm Not <a href="http://www.TheLittleEngineers.org/pages/reference/20200103/IMDb/JackieChan.htm" target="_blank">Jackie Chan</a>.<br>I Did Enjoy That Film Immensely.</h2>
<p align="justify">The headline of this paragraph is merely an attempt at humor while allowing me the opportunity to mention a <a href="http://www.TheLittleEngineers.org/pages/reference/20200103/IMDb/WhoAmI.htm" target="_blank">film</a> that my son and I quite thoroughly enjoyed when it was released during his childhood in 1998, leading to his eventual love of <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/IMDb/JackieChanAdventures.htm" target="_blank">&quot;The Jackie Chan Adventures&quot;</a> animated series, which would be released some two years later in 2000. Most of the world seemed to be concerned with the overhyped <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/Y2K/Y2KBug.htm" target="_blank">&quot;Y2K Bug&quot;</a> and we were just watching <a href="http://www.TheLittleEngineers.org/pages/reference/20200103/IMDb/JackieChan.htm" target="_blank">Jackie</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/IMDb/JackieChanAdventures.htm" target="_blank">Chan</a> and enjoying our lives while playing <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/NickMarentes/CosmicAmbush.htm" target="_blank">&quot;Cosmic Ambush&quot;</a> and <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/GoSub/TheCrystalCityGitHub.htm" target="_blank">&quot;</a><a href="http://www.TheLittleEngineers.org/pages/reference/20200112/GoSub/GoSubZenixTheCrystalCity.htm" target="_blank">The</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/GoSub/JeremySpillerResume.htm" target="_blank">Crystal</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/GoSub/SixtyFramesPerSecondOrBust.htm" target="_blank">City</a><a href="http://www.TheLittleEngineers.org/pages/reference/20200112/GoSub/TheCrystalCityGitHub.htm" target="_blank">&quot;</a> on our 512K CoCo 3. The following text serves as a general Introduction to <a href="mailto:TheLittleEngineers@OutLook.com" target="_blank">Robert</a> <a href="mailto:LittleEngineer_RAT@OutLook.com" target="_blank">&quot;The R.A.T.&quot;</a> <a href="mailto:OurLittleEngineers@gMail.com" target="_blank">Allen</a> <a href="mailto:LittleEngineer.RAT@gMail.com" target="_blank">Turner</a>, <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Zombie</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Software</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/ZombieSoftwareSystems" target="_blank">Systems</a>, <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/BinarySystems" target="_blank">Binary</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/BinarySystems" target="_blank">Systems</a>, <a href="https://www.facebook.com/OurLittleEngineers/" target="_blank">The</a> <a href="https://www.facebook.com/groups/985537051651794/" target="_blank">Little</a> <a href="https://www.facebook.com/TheLittleEngineers.org" target="_blank">Engineers</a><a href="https://www.facebook.com/groups/566741160795144/" target="_blank"></a>, <a href="http://www.TheLittleEngineers.org/" target="_blank">TheLittleEngineers.org</a>, <a href="https://www.facebook.com/tincansandducttape/" target="_blank">Tin</a> <a href="https://www.facebook.com/groups/1654785514796788/" target="_blank">Cans</a> <a href="https://www.facebook.com/Tin-Cans-Duct-Tape-728969003939754/" target="_blank">And</a> <a href="https://www.facebook.com/groups/1828354620822631/" target="_blank">Duct</a> <a href="https://www.facebook.com/groups/228910954180459/" target="_blank">Tape</a>, <a href="http://www.tincansandducttape.com/" target="_blank">TinCansAndDuctTape.com</a>, <a href="http://www.tcadt.com/" target="_blank">TCADT</a>, <a href="http://www.tcadt.com/" target="_blank">TCADT.com</a>, <a href="http://www.CannedLogic.com/" target="_blank">Canned Logic</a>, <a href="http://www.CannedLogic.com/" target="_blank">CannedLogic.com</a>, <a href="http://www.RetroATX.com/" target="_blank">RetroATX</a>, <a href="http://www.RetroATX.com/" target="_blank">RetroATX.com</a>, <a href="http://www.Retro-ATX.com/" target="_blank">Retro-ATX</a>, <a href="http://www.Retro-ATX.com/" target="_blank">Retro-ATX.com</a>, <a href="http://www.RoboCircuits.org/" target="_blank">RoboCircuits</a>, <a href="http://www.RoboCircuits.org/" target="_blank">RoboCircuits.org</a>, <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip</a> and <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a>. Please note that the <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> domain was acquired by <a href="mailto:TheLittleEngineers@OutLook.com" target="_blank">Robert</a> <a href="mailto:LittleEngineer_RAT@OutLook.com" target="_blank">&quot;The R.A.T.&quot;</a> <a href="mailto:OurLittleEngineers@gMail.com" target="_blank">Allen</a> <a href="mailto:LittleEngineer.RAT@gMail.com" target="_blank">Turner</a> on December 25, 2018 from the prior owners, who happen to be his brother (J.R. a.k.a. John Robert a.k.a. &quot;Big John&quot;) and nephew (J.E. a.k.a. John Eric a.k.a. &quot;Little John&quot;). As such, <a href="mailto:LittleEngineer.RAT@OutLook.com" target="_blank">&quot;The R.A.T.&quot;</a> is unable to answer any inquiries regarding any products or services of <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> prior to that date simply because I have no knowledge of the site. I have attempted to utilize the <a href="http://www.TheLittleEngineers.org/pages/reference/20200103/GIMEchip/GIMEchipWayBackMachine.htm" target="_blank">Internet Archive WayBack Machine</a> to have a look at the <a href="http://www.TheLittleEngineers.org/pages/reference/20200103/GIMEchip/GIMEchipWayBackMachine.htm" target="_blank">site</a> at various stages of existence, but there seems to be very little there as of the date of this writing (April 10, 2019). <a href="mailto:LittleEngineer_RAT@OutLook.com" target="_blank">&quot;The R.A.T.&quot;</a> has also acquired the rights to all products previously produced by <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> and its previous owners. As part of the acquisition agreement, all of those products will be released as open source, under a <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License, as time and resources permit. Note that some of these products were previously released by my brother under an <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/OSHWA.htm" target="_blank">Open Source Hardware License</a> and all of those releases remain available under that license. Making certain that any given product meets all of the requirements necessary for the <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/OSHWA.htm" target="_blank">OSHWA</a> license is a time consuming task when preparing older archives for release and so I have decided to utilize a <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License for any releases prepared by myself. This should allow you to utilize the releases in almost any desired manner, including commercial, within the terms of the license.</p>
<h3 align="center">Introducing <a href="mailto:TheLittleEngineers@OutLook.com" target="_blank">T</a><a href="mailto:LittleEngineer_RAT@OutLook.com" target="_blank">h</a><a href="mailto:OurLittleEngineers@gMail.com" target="_blank">e</a> <a href="mailto:LittleEngineer.RAT@gMail.com" target="_blank">&quot;</a><a href="mailto:TinCansAndDuctTape@gMail.com" target="_blank">R</a><a href="mailto:CannedLogic@gMail.com" target="_blank">.</a><a href="mailto:TinCansAndDuctTape@OutLook.com" target="_blank">A</a><a href="mailto:LittleEngineer.RAT@OutLook.com" target="_blank">.</a><a href="mailto:TheLittleEngineers@OutLook.com" target="_blank">T</a><a href="mailto:LittleEngineer_RAT@OutLook.com" target="_blank">.</a><a href="mailto:OurLittleEngineers@gMail.com" target="_blank">&quot;</a></h3>
<p align="justify">I have started writing this introduction numerous times only to get sidetracked and derailed. Hopefully, I will be able to properly introduce myself this time. I will begin at the acquisition of my first personal computer, a Sinclair ZX81 Issue 3, produced by Timex and sold as the TS1000 (Timex Sinclair 1000 or T/S1000). This would be March 30, 1982 - My fourteenth birthday. My parents presented me with a Timex Sinclair 1000 (TS1000) computer, after much begging and pleading. The TS1000 is a ZX81 with a few differences: 2K of RAM, an [ENTER] key instead of [NEW LINE] or [N/L] and Timex branding. I had wanted a computer for so long, and Sir Clive Sinclair succeeded in making it affordable. Timex made it even more affordable as the TS1000 was placed on sale for $59.99 at the local "Big B" drug store, at the time, a division of Brunos Corporation (Food World, Food Fair, Consumer Warehouse, etcetera). I was ecstatic - I finally had a computer, and as limited as it was, I still mamaged to learn a great deal from that machine. This experience with the ZX81 (T/S1000) led to the creation of Zombie Software Systems, my first computer venture. When Timex announced the Timex Sinclair 2068 (TS2068) after canceling the TS2000 (a 48K Spectrum clone), I knew that I wanted it to be my next computer and my parents agreed to buy it for me for Christmas of 1983. Then, it happened: I walked into the local franchised Radio Shack store, operated at the time by Cisco Auto Parts, and there, on display right next to the entrance, was the newly introduced Color Computer 2 with 16K of RAM and Extended Color BASIC. It took mere moments for me to fall in love with that machine and I asked my parents for the Color Computer 2 instead of the TS2068. They placed it on lay-a-way as Christmas approached. It was eventually paid off and sat under the Christmas tree until Christmas Evening of 1983. They allowed me to open it on Christmas Evening and I was up all night working through the programs in the manuals. It was wonderful. This led to the creation of Binary Systems, my second computer venture. Eventually, I came across an advertisement in Radio-Electronics from a company by the name of Unicorn Electronics (a company that remains in business until this very day). They had a set of 4164 Dynamic RAM chips with a 150nS access time for, I think $9.95 (although I seem to remember $1.50 each, so perhaps it was $1.50 per chip or 8/$9.95). The chips were used but tested pulls. I ordered them, along with a bag of keyboard switches (intended to be used for building a better keyboard for my TS1000 and adding four function keys to the CoCo 2). When they arrived, I opened the case of my Color Computer 2, installed the 64K chips, soldered in the <b>W1</b> <em>jumper</em> and voila - I had a 64K ECB Color Computer 2. Although other systems of the time had better graphics and sound, the Color Computer line of systems by Radio Shack, a division of Tandy Corporation, would become (and remain) my favorite computers of all time. In fact, I still use them to this very day, having kept one Color Computer 3 (CoCo 3) when I passed my vintage computing collection to my brother, J.R. (John Robert) who then passed it on to his son, &quot;Little John&quot; (John Eric), but I will get to that after a brief reminiscence of ZSS and BS, as follows:</p>
<h3 align="center">ZSS or Zombie Software Systems:</h3>
<p align="justify">Zombie Software Systems was formed on my fourteenth birthday, 30 March 1982, as a sole proprietorship supporting the Timex and Sinclair computer systems.</p>
<h3 align="center">Supported systems initially included:</h3>
<p align="justify"><ul align="justify">
<li align="justify">Sinclair ZX80</li>
<li align="justify">Sinclair ZX81</li>
<li align="justify">Timex Sinclair 1000</li>
</ul>
<h3 align="center">Support was eventually added for:</h3>
<ul align="justify">
<li align="justify">Timex Sinclair 1500</li>
<li align="justify">The PC-8300 "Your Computer"</li>
<li align="justify">Sinclair Spectrum (All Versions)</li>
<li align="justify">Timex Sinclair 2068</li>
<li align="justify">Sinclair QL</li>
</ul>
<p align="justify">By 1991, and in conjunction with Binary Systems, support had been added for machines from Mattel, Atari, Tomy, Texas Instruments, Tandy Radio Shack, Commodore and many others.</p>
<h3 align="center">BS or Binary Systems:</h3>
<p align="justify">Binary Systems was formed on 23 December 1983, as a sole proprietorship supporting the Tandy Radio Shack computer systems.
<h3 align="center">Supported systems initially included:</h3>
<ul align="justify">
<li align="justify">TRS-80 Color Computer (CoCo 1)</li>
<li align="justify">Tandy Data Products TDP-100</li>
<li align="justify">TRS-80 Color Computer 2 (CoCo 2)</li>
<li align="justify">Dragon Data Dragon 32</li>
<li align="justify">Tano Dragon 64</li>
<li align="justify">TRS-80 Model I</li>
</ul>
</div>
<!-- /Top Left Column -->

<!-- Top Right Column -->
<div class="column" style="background-color:WhiteSmoke;" align="center">
<h3 align="center">Support was eventually added for:</h3>
<ul align="justify">
<li align="justify">TRS-80 Model III</li>
<li align="justify">TRS-80 Model IV</li>
<li align="justify">TRS-80 Model 4/4P</li>
<li align="justify">Tandy Color Computer 3</li>
</ul>
<p align="justify">By 1991, and in conjunction with Zombie Software Systems, support had been added for machines from Mattel, Atari, Tomy, Texas Instruments, Sinclair, Commodore, Amstrad, Kaypro and many others. The operation of Zombie Software Systems and Binary Systems was a labor of love more than anything else, as it never made a profit, but it was fun and remains among the best memories of my youth and early adulthood and I am thankful that the stroke
(see below) did not take these memories from me.</p>
<p align="justify">I continued to support these vintage machines until 2007 when I suffered a stroke. At that point, I passed operations on to my son, John (he and his cousin share both
the same name and same date of birth through a very odd coincidence). My son eventually made a mess of things and finally moved on to other hobbies. A side effect of the stroke was that I lost almost all interest in
computers and electronics, vintage and otherwise. It was thus that I presented my entire collection of vintage computers and electronics to my brother J.R. (John Robert or &quot;Big John&quot;). He took the opportunity to bond
with his son, J.E. (John Eric or &quot;Little John&quot;). &quot;Little John&quot; was facing a number of health issues, but he jumped in with both feet, teaching himself all about the Color Computer and other systems. He began to develop
a plethora of hardware projects for the Color Computer and other vintage systems. The earliest of his designs were rubbish due to his lack of skill, but he appears to have learned rather quickly, producing some amazing
designs. I have taken it upon myself to "redo" his earliest works, hopefully producing manufacturable products from them. The first of his designs to receive the "redesign" treatment from me is the &quot;FlexiMIDI&quot;, &quot;FlexiROM&quot;
and &quot;FlexiBuffer&quot; projects. Those three designs were excellent in concept, but rubbish in practice due to his lack of circuit design skills at the time that he developed them. They are certainly worth the time and effort
to redesign. He would eventually become disillusioned and abandon the hobby altogether. This was, in no small part, due to hackers repeatedly taking down his website: <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a>. They (the unknown hackers) eventually
compromised his eBay and PayPal accounts, rendering them completely useless. That was the straw that broke the camels back, so to speak. He (&quot;Little John&quot;) gave up and moved to Tennessee. He left everything with his
father, my brother, and asked that his father release all of his works as open source. J.R. made several valiant efforts to honor that request, but never fully succeeded in releasing all of the works of &quot;Little John&quot;.
Fast Forward almost a decade...</p>

<h3 align="center">The Beginning of a Family Tragedy:</h3>
<p align="justify">November of 2018, my father, Robert Embry Turner fell ill and was hospitalized. As Christmas approached, he remained in the hospital. Many family members visited and it came to pass that I reconnected with J.R. and &quot;Little John&quot;. They asked me if I would like to have my old vintage computing collection back. At first, I was hesitant and uninterested. As my fathers condition worsened, I began to remember how hard my father worked to buy me those first computers. Tons of memories, good and bad, began to flood my mind. I decided to accept their offer. In addition to the hardware and software, they presented me with the <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> domain name. This became my Christmas present from my brother and his son. &quot;Little John&quot; asked that I finish what his father started: the release of all of  &quot;Little John's&quot; work as open source. I reluctantly agreed, though I was unsure if I could ever manage the time and effort to do so. I honestly was not prepared to take on such a monumental task. Then, tragedy struck.
<br><br>
On the day of January 4, 2019, my father died as I held his hand in that hospital room. His death had quite a profound effect on me. I almost lost my job while trying to come to terms with never being able to speak to my father again. I eventually began to recover, to an extent, but I began to think of everything and everyone that I had lost over the years. For one thing, my own son, also named John Eric Turner, and I are estranged. We "speak" online, but I have not seen him in a very long time<a href="#son">*</a>. He was unable to be at the hospital and did not get to say goodbye to my father before he died. As mentioned, my son and his cousin are both named John Eric Turner, and there is a story behind it, however, for the moment, suffice it to say that they both were named In Memory of Jon-Erik Hexum, who died on the set of "Cover Up" on Friday, October 12, 1984. As my mind wandered, I thought of my mother in law, Sarah Ann Channell, who passed away on January 12, 2003 and my father in law, Frank Leon Channell, who passed away on August 23, 2003. Even though I was divorced from their daughter, they were still family and their deaths were very painful to me and my son. Indeed, their deaths affected my son in such a way that he never fully recovered and that is partially what eventually led to our falling out in 2007 or 2008 and the resulting estrangement. I am sure that my addled state after that stroke also played a hand in the troubles between my son and I because I became very difficult to be around. Thinking about Sarah and Frank caused me to really begin missing my son and, even more, my father. I then thought about my best friend from high school, David Ray Poe, who died on May 20, 2013. Eight days prior to his death, he had sent me an email that I did not see until after he died. That email was a single sentence: "Did you die?". You can perhaps imagine the effect that reading the message had on me. In reality, he would often send a message like that when he had not heard from me in a while. Another close friend from high school, Steve Allen Cox, died on September 6, 2016. As all of the thoughts of everything and everyone that I had lost flooded my mind, I began to spiral and was in peril of losing myself. I needed a distraction, something to keep my mind occupied and perhaps aid in my coming to terms with the death of my father. I found that distraction in the form of that vintage computing collection and the projects that &quot;Little John&quot; had created. It is for that reason alone that you are now reading this and seeing those products, which I have decided to release under a <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License. What this means is that you, or anyone else for that matter, may use the products in almost any way that you may desire, even commercially. I am doing all of this to honor the memory of my father, Robert Embry Turner, and everyone else that I have lost. I truly hope that these products provide much enjoyment to all who discover them. I should point out that I have absolutely no desire to revive the <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> website, primarily because I do not have all of the files necessary to recreate <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a>. It is very likely that I will stumble across some or all of the <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> website files as I begin to inventory everything that was included with my 2018 Christmas gift from &quot;Big and Little John&quot;. I also DO NOT wish to invoke the ire of those hackers who targeted my nephew and destroyed his website, eBay and PayPal accounts. I will very likely, however, forward the <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a> domain to a page on my <a href="http://www.TheLittleEngineers.org/" target="_blank">http://www.TheLittleEngineers.org/</a> website or perhaps I will forward it to the GitHub page - I am currently undecided.

So, there you have it - most of what I wanted to say about how I came to posses all of the works of my nephew and his father, as well as their domain name, <a href="http://www.GIMEchip.com/" target="_blank">GIMEchip.com</a>. In addition to releasing all of their products under a <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License, I will also be releasing all of the Zombie Software Systems and Binary Systems products under identical licensing terms.</p>
  </div>
  </div>
  <hr>
<!-- /Top Right Column -->
 
<!-- Center Row -->
<p align="center">
<font size="6">Is ALL of this really FREE?<br></font>
<font size="5"><em>YES!</em></font>
</p>
<p align="justify" id="support">
Everything contained in the GitHub Repositories for these projects is free to use, even commercially, in accordance with the terms of the <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a>License. The Amazon Kindle and Paperback Publications, however, are not licensed for redistribution and are only available to our Patrons as a free ".PDF" or for purchase from Amazon. These particular publications help to generate revenue that is used for further developmental efforts. It is not necessary to purchase these publications in order to make use of the GitHub Repositories, however, such purchases provide the funds necessary for the development of future products. The repositories contain all necessary information needed to construct, assemble and use the products described therein. If you would like to support our continued developmental efforts, the remaining paragraphs detail several methods that may be used to offer support of our work.

As stated, I have absolutely no intention of charging any fees whatsoever in regards to the use of these products. Anyone who so desires may manufacture and sell any of these products, though they must state specifically that they will be providing any and all support as may be required. However, If you would care to support my work, donations are happily accepted, whether they be in the form of funds, vintage computing equipment, tools, components, etcetera. I am always in need of such items. I specifically need PAL versions of the TRS80 Color Computer series (1,2 and 3) as well as NTSC/PAL Dragon D32, D64, D200, etcetera for developmental purposes. Monetary donations help to support the hosting needs of http://www.TheLittleEngineers.org/ as well as the development and manufacture of the prototype Printed Circuit Boards.

Perhaps the easiest and most beneficial method of supporting The Little Engineers (monetarily) would be by becoming a <a href="https://www.patreon.com/TheLittleEngineers" target="_blank">Patron</a> on <a href="https://www.patreon.com/TheLittleEngineers" target="_blank">Patreon</a>. The following are among the benefits offered to <a href="https://www.patreon.com/TheLittleEngineers" target="_blank">Patrons</a>. <a href="https://www.patreon.com/TheLittleEngineers" target="_blank">Patrons</a> will receive several exclusive benefits, such as:
<p align="justify" id="patreon"><ul align="justify">
<li align="justify">FREE copies of ANY of our detailed Theory of Operation and Assembly e-books relating to our projects.
</li>
<li align="justify">Random giveaways of bare Printed Circuit Boards (PCB's) developed by The Little Engineers.
</li>
<li align="justify">Random giveaways of Kits developed by The Little Engineers.
</li>
<li align="justify">Random giveaways of assembled projects developed by The Little Engineers.
</li>
<li align="justify">The opportunity to purchase various bare Printed Circuit Boards (PCB's) developed by The Little Engineers at discounts of up to 50% off.
</li>
<li align="justify">The opportunity to purchase various Kits developed by The Little Engineers at discounts of up to 50% off.
</li>
<li align="justify">The opportunity to purchase various assembled projects developed by The Little Engineers at discounts of up to 50% off.
</li>
</ul>
<p align="justify">
We will also be publishing detailed Theory of Operation and assembly manuals for all of our open source products in e-book and paperback formats. Purchases of these e-books and/or paperbacks helps to support The Little Engineers and our continued developmental efforts. Donations may also be made in almost any variety of digital currency, including, but not limited to, the following:</p>
<p align="justify" id="digitalcurrency"><ul align="justify">
<li align="justify">BitCoin (BTC):<br>
bc1q7m3vmafshmkhz29ec8tayx3704qaa8xxhhadf5
</li>
<li align="justify">Ethereum (ETH), Ethereum Classic (ETC), Callisto (CLO) or any ETH, ETC or CLO based tokens:<br>
0xBc306a88F17cb88DaDcBB80A60E8a93E9B74558c
</li>
<li align="justify">BitCoin Cash (BCH):<br>
qr6d8mjm4fr90ryyywkhs578f0lgn7e5guue964rqz
</li>
<li align="justify">BitCoin Gold (BTG):<br>
GagaV6V46oLNzuJq1RrHzQuZXB9KvQDuv7
</li>
<li align="justify">BitCoin SV (BSV):<br>
1NVRHunKywVvkh1MgMFUQLUxEFUBxPk4vy
</li>
<li align="justify">LiteCoin (LTC):<br>
LKinnpFBxf2F8ZwTivYwLRtbX99bB9qcCE
</li>
<li align="justify">Cardano (ADA):<br>
DdzFFzCqrhsnVi7hPhGzUVeoMk2xmQvN4i4uMRUi2RED8TtsVKqj4vXY3QxEC9HbVXWrequmqemHyzEQDNcX2246tSH6jQEv1cmU7yzX
</li>
<li align="justify">Stellar Lumens (XLM):<br>
GAUVDHXFDAF36IM267NW2XOHOWAUJ7VFEXSRFBCIHHLG53IZIDXRZBX5
</li>
<li align="justify">Ripple (XRP):<br>
rp4rfoceHEdpUpp8z5r5AnS27t1JMY7j3a
</li>
<li align="justify">Binance Coin (BNB):<br>
bnb1fzyxmu2f9t5dcvccjrzjpkvye7fpgd7rwlzxfk
</li>
<li align="justify">TRON (TRX), BitTorrent (BTT), WINk (WIN), Tether USDT (TRX-USDT) or any TRX based tokens:<br>
TRx67xS64bTuoVBxE67gcirhttWuZhrVTv
</li>
<li align="justify">Multi-Collateral DAI (DAI), Compound DAI (CDAI) or Old DAI (SAI):<br>
0xBc306a88F17cb88DaDcBB80A60E8a93E9B74558c
</li>
<li align="justify">DogeCoin (DOGE):<br>
DQBceUqt9tY4SXqFNf1BWVmDjQ1hRZyzs5
</li>
<li align="justify">ARK (ARK):<br>
AXGgC9t1Xk7Pcb6cjGB2cAhfkiriNnpBP3
</li>
<li align="justify">Cosmos (ATOM):<br>
cosmos1wjwzc0j8y0nj6ua63qx98y2r3d7sjdnl77zs28
</li>
<li align="justify">Dash (DASH):<br>
XdwuZTLt3uwKF25J6wPvDxKqUdESkQfqgE
</li>
<li align="justify">Decred (DCR):<br>
DsbsetxhafJQF9qu5gNs39pEq8RFDLZW64P
</li>
<li align="justify">DigiByte (DGB):<br>
DApgQ4EwJHhkG1wEGr1dCmbB8ScuWw47kG
</li>
<li align="justify">EOS (EOS), eosDAC (EOSDAC) and EOS based Tokens:<br>
gu4dkmbzhege
</li>
<li align="justify">Lisk (LSK):<br>
982485030507303108L
</li>
<li align="justify">Monero (XMR):<br>
45m8V8NCb3EDabWDpAV4UD6bXamiPAwXAEq2LGk1xGfYTxrUcB9a2Q7CHPZnkhAccMbk5WRAWHxcqV1Kc8XZ3xrCDPq6JTg
</li>
<li align="justify">Nano (NANO):<br>
nano_15kt9phu8cqnq9yfrbxosanea1uzhwi6cfb9o4m5sssnzjx8ze4fh97qrbso
</li>
<li align="justify">NEM (XEM):<br>
NDR2OOXGUB3BQUPEMW3THRJDVA2RKHQVQ2Z5YH6C
</li>
<li align="justify">NEO (NEO) and NEO Gas (GAS):<br>
AUjkYDiYNwkinqCJqhvdoyszufhjrxDRar
</li>
<li align="justify">Ontology (ONT) and Ontology Gas (ONG):<br>
ASEoXkbtnKf7k2uxF2uq8xpRugDKeMbSpN
</li>
<li align="justify">Qtum (QTUM):<br>
QbJQz4CMSFbb3UTMdho37mLJ2qHVMJv2w6
</li>
<li align="justify">RavenCoin (RVN):<br>
RQA7YVbuoVquwKUZnz4gqTqLfWmxX7euBY
</li>
<li align="justify">Tezos (XTZ):<br>
tz1RSMFcmgCC2VhLzRKEcAVbFqxjnBmVW1mR
</li>
<li align="justify">Waves (WAVES):<br>
3PJpQ2tkYwgUnSzz1NXSbEQjMuEUcULeiLg
</li>
<li align="justify">Zcash (ZEC):<br>
t1NYL2BXuaGnkScy1MZjc9XPJg5fva29dRB
</li>
<li align="justify">RSKMainNet (RBTC):<br>
0xbE3e3b4B06FD3617b0d2b256cd1Aab6159157e7a
</li>
<li align="justify">Unity (JXX):<br>
0x86FfA1eA3B5A67996f1f33Bb7BF20D0b69eCF6ae
</li>
<li align="justify">BitCore (BTX):<br>
2QeVXDYLJe85FCZDbTWfnhavsmxv65vLN2
</li>
<li align="justify">GroestlCoin (GRS):<br>
FVVvtdDPNw35cywDCDgxb8MBqArf3YSnJw
</li>
<li align="justify">Kin (KIN):<br>
GBHLFZALLF75COCK52GB4HNMRYPM2Q33XZ6H3FW5EC54S4F7IPISZHIU
</li>
</ul>
<p align="justify">
Should you wish to use digital currency, I highly recommend checking out this referral link: <a href="https://www.coinbase.com/join/turner_sep" target="_blank">Digital</a> <a href="https://www.coinbase.com/join/turner_sep" target="_blank">Currency</a>. Signing up from that <a href="https://www.coinbase.com/join/turner_sep" target="_blank">link</a> also helps The Little Engineers in the long run. If you would like to make a donation by some other means, feel free to contact me by e-mail or  FaceBook Messenger. Please note, however, that donations are completely optional, but they do help to further product development. All products developed by The Little Engineers are completely free to use under the terms of the <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSA.htm" target="_blank">Creative Commons Attribution-ShareAlike 4.0 International</a> <a href="http://www.TheLittleEngineers.org/pages/reference/20200112/CreativeCommons/CCBYSALegalCode.htm" target="_blank">(CC BY-SA 4.0)</a> License, even for commercial purposes.</p>
<p align="justify"><ul align="justify">
<li align="justify">Please consider subscribing to our <a href="https://www.youtube.com/channel/UCgAwso8p5hkLFN9AdN6oxQg" target="_blank">YouTube</a> <a href="https://www.youtube.com/channel/UCgAwso8p5hkLFN9AdN6oxQg" target="_blank">Channel:</a><br>
<a href="https://www.youtube.com/channel/UCgAwso8p5hkLFN9AdN6oxQg" target="_blank">https://www.youtube.com/channel/UCgAwso8p5hkLFN9AdN6oxQg</a></li>
<li align="justify">Please follow us on <a href="https://twitter.com/TLEngineers" target="_blank">Twitter</a>:<br><a href="https://twitter.com/TLEngineers" target="_blank">https://twitter.com/TLEngineers</a></li>
<li align="justify">Please check us out on <a href="https://www.twitch.tv/thelittleengineers" target="_blank">Twitch</a>:<br><a href="https://www.twitch.tv/thelittleengineers" target="_blank">https://www.twitch.tv/thelittleengineers</a></li>
<li align="justify">Please consider following us on <a href="https://www.instagram.com/thelittleengineers_org/" target="_blank">Instagram</a>:<br><a href="https://www.instagram.com/thelittleengineers_org/" target="_blank">https://www.instagram.com/thelittleengineers_org/</a></li>
<li align="justify">Please follow us on <a href="https://github.com/TheLittleEngineers?tab=repositories" target="_blank">GitHub</a> in order to access all of our projects:<br><a href="https://github.com/TheLittleEngineers" target="_blank">Github</a>.</li>
</ul>
<p align="justify">
Thank You for your time. I hope that you enjoy using these products as much as I enjoyed developing them (or debugging them in the case of the designs produced by my nephew and his father). - Robert &quot;The R.A.T.&quot; Allen Turner
</p>
<hr>
<!-- /Center Row -->

<!-- Bottom Left Column -->
<div class="row" style="background-color:WhiteSmoke;" align="center">
<div class="column" style="background-color:WhiteSmoke;" align="center">
<p align="center">
<h2 align="center"><font size="6">Trials and Tribulations</font></h2>
<font size="5"><em>August 5, 2019 through December 7, 2019 and beyond</em></font></h2>
<p align="justify" id="son">
*You may have noticed the asterisk (*) in the preceding text in reference to my not having seen my son for quite some time. Events to occur the week of August 5, 2019 would rectify that situation but at no small cost to me. Suffice it to say that my health took a bit of a downward turn resulting from no less than nine sets of symptoms/conditions which culminated in open heart surgery eight weeks ago (as of December 7, 2019). My son drove for many hours and stayed with me up until the day of the surgery at which time he had to return to work. Below, I have listed my discharge diagnosis which lists all nine of these in roughly the order of their occurence, keeping in mind that this all happened to me between August 2019 and November 2019.<br><br>
<center><b><big>Discharge Diagnosis:</big></b><br></center>
<ol align="justify">
<li align="justify">CHF:Congestive Heart Failure</li>
<li align="justify">RG:Reflux Gastritis including a near fatal infection resulting in colitis</li>
<li align="justify">CDD:C5/C6 Degenerative Disease</li>
<li align="justify">HTN:Hypertension</li>
<li align="justify">HLD:Hyperlipidemia</li>
<li align="justify">HM:Hypomagnasemia</li>
<li align="justify">HC:Hypocalcemia</li>
<li align="justify">CAD:Coronary Artery Disease</li>
<li align="justify">ABLA:Acute Blood Loss Anemia</li>
</ol>
<p align="justify">Now, with that being said, I am doing just fine and have recovered nicely. However, our family was struck with yet more bad news.</p>
  </div>
<!-- /Bottom Left Column -->  

<!-- Bottom Right Column -->
<div class="column" style="background-color:WhiteSmoke;" align="center">
<p align="center">
<h2><font size="6">Multiple Myeloma</font></h2>
<font size="5"><em>Cousin William Lee</em></font>
</p>
<p align="justify">
Almost two weeks into the the &quot;New Year of 2020&quot;, on the date of January 12, 2020, the family received even more bad news. My cousin William, the son of my mothers sister, was diagnosed with blood cancer, specifically multiple myeloma. His condition is terminal, although the physicians are optimistic that, with treatment, He can expect somewhere between five and ten years. This was yet another crushing blow to the family.<br><br>I suppose that my life has reached a point to where I dread the coming of each new day for the news that it may bring. However, I shall endevor to persevere whilst immersing myself into the day to day operations of &quot;<a href="http://www.RetroATX.com" target="_blank">Retro</a><u>-</u><a href="http://www.Retro-ATX.com" target="_blank">ATX</a>&quot; and &quot;<a href="http://www.TheLittleEngineers.org/" target="_blank">The Little Engineers Project</a>&quot;. I hereby extend my gratitude to one and all for your continued <a href="#digitalcurrency">support</a> and <a href="https://www.patreon.com/TheLittleEngineers" target="_blank">encouragement</a>. May God Bless You and Yours. I remain sincerely yours, <em>Robert &quot;The R.A.T.&quot; Turner</em>.
</div>
<!-- /Bottom Right Column -->
</div>
</body>
</html>



