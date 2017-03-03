<h1><center><font color="black" size = "5px" face=Family style="line-height:1;">Working Summary(No.1)</font></center></h1>
<center><font face=Family size='3px' style="line-height:1;">Yangyang Li</font></center>
<center><font size='3px' face=Family>2017.3.1</font></center>

<font color='336699' size=4px face='Arial' ><B>1.Introduction</B></font>
<p style='text-indent:2em' ><font size='3px' face=Family >For the following work and the knowledge of the future project, the preparation work had been completed in these two weeks, which is aimed to select targets(binary stars)from WDS catalog and get cross-match with other catalogs using the proper motion information of binary stars, mainly PPMXL, Pan-StarrS1 and Gaia DR1, because we need to select those that are physically associated. After applying the consistent proper motion standard to the catalog, we can remove the unreliable systems or optical binaries. Here we use the 3-σ judgement to exclude the unqualified systems. The original WDS catalog contains 138999 systems. After the match between WDS and PPMXL, we get 45273 binary stars from 96528 systems which have positions and complete proper motion information in PPXML catalog while reducing the number to 6785 after the match with Gaia DR1.</font></p>
<font size='4px' color='33669' face='Arial'>
<B>2.Selecting Process</B></font>
<p style='text-indent:2em'><font size='3px' face=Family>In the intial WDS catalog, we have 138999 systems. But some of the systems miss their coordinates and proper motion of the primary and secondary stars. We exclude those systems and get 96528 systems back from PPXML catalog server when setting the searching radius is within 5 arcsecond. And we find these systems are well-distributed in globle sky map except the polar regions.(<B>Fig.1</B>)</font>
<center><figure>
    <img src="https://raw.githubusercontent.com/Li-Yangyang/Markdown-Resources/master/Markdown/Pics/PPMXL_Global2.png" alt="This is the figure caption" id="fig_id" title="This is where the title goes" >
    <figcaption><B>Fig.1</B> 96528 WDS systems from PPXML catalog server <br>when setting the searching radius within 5 arcsecond</figcaption>
</figure></center>

<p><font size=3px face=Family>Before we get the consistent systems in PPMXL which are within 3-σ, the consitency of proper motions from two catalogs distributed far beyong our standard. However, when we finish the match, we can get the proper motions in WDS catalog more reliably.(<B>Fig.2</B>)After matching with PPMXL, 45273 binary systems are obtained.</font></p>

<center><figure>
    <img src="https://raw.githubusercontent.com/Li-Yangyang/Markdown-Resources/master/Markdown/Pics/initial_wds_ppmxl_PM1unt_hist.png" alt="Before proper motion consitency check for single system" id="fig_id" title="This is where the title goes" >
    <figcaption><B>Fig.2(a)</B> Before proper motion consitency between WDS and PPMXL check for primary stars</figcaption>
    <img src="https://raw.githubusercontent.com/Li-Yangyang/Markdown-Resources/master/Markdown/Pics/after_first_match.png" alt="Before proper motion consitency check for binary stars" id="fig_id" title="This is where the title goes" >
    <figcaption><B>Fig.2(b)</B> Before proper motion consitency check for binary stars</figcaption>
</figure></center>

<p style='text-indent:2em'><font size='3px' face=Family>Then we continue the matching with Gaia DR1 with 43567 systems found in Gaia DR1 catalog. It is somewhat confusing that a lot of systems which we have validated in PPMXL are not meet the 3-σ standard when we apply the Gaia catalog, which means that the deviation of proper motion is large than the previous ones(<B>Fig.3(a)</B>). And <B>Fig.3(b)</B> describes the final uncertainty(the deviation between primary and second stars) for selected binary stars</font></p>

<center><figure>
    <img src="https://raw.githubusercontent.com/Li-Yangyang/Markdown-Resources/master/Markdown/Pics/initial_wds_ppmxl_gaia_PMunt_hist.png" alt="Before proper motion consitency between WDS,PPMXL and Gaia DR1 check for primary stars" id="fig_id" title="This is where the title goes" >
    <figcaption><B>Fig.3(a)</B> Before proper motion consitency between WDS,PPMXL and Gaia DR1 check for primary stars</figcaption>
    <img src="https://raw.githubusercontent.com/Li-Yangyang/Markdown-Resources/master/Markdown/Pics/after_second_match.png" alt="Before proper motion check for binary stars among WDS,PPMXL and Gaia DR1" id="fig_id" title="This is where the title goes" >
    <figcaption><B>Fig.3(b)</B> Before proper motion check for binary stars among WDS,PPMXL and Gaia DR1</figcaption>
</figure></center>

<font size='4px' color='33669' face='Arial'>
<B>3.Results</B></font>
<p style='text-indent:2em'><font size='3px' face=Family>Finally we get 6785 reliable WDS binary-stars systems matching with PPMXL and Gaia DR1. But we have't match with Pan-StarrS1 because of its late data realise in the mid of March.

<center><figure>
    <img src="https://raw.githubusercontent.com/Li-Yangyang/Markdown-Resources/master/Markdown/Pics/final_binary_stars_map.png" alt="This is the figure caption" id="fig_id" title="This is where the title goes" >
    <figcaption><B>Fig.4</B> Final WDS binary systems after matching with PPMXL and Gaia DR1</figcaption>
</figure></center>




