自用clash科研规则，避免如校园网无法IP认证这些网站

![image](https://github.com/xylx521/Rule/blob/master/assets/image-20240111143312723.png)

```clash
    - DOMAIN-SUFFIX,deepl.com,DIRECT
    - DOMAIN-SUFFIX,manual.gromacs.org,DIRECT
    - DOMAIN-KEYWORD,sci-hub,DIRECT
    - DOMAIN-SUFFIX,ccdc.cam.ac.uk,DIRECT
    - DOMAIN-KEYWORD,wiley,DIRECT
    - DOMAIN-KEYWORD,pubs,DIRECT
    - DOMAIN-KEYWORD,translate,DIRECT
    - DOMAIN-KEYWORD,docs,DIRECT
    - DOMAIN-KEYWORD,onenote,DIRECT
    - DOMAIN-KEYWORD,office,DIRECT
    - DOMAIN-SUFFIX,digicert.com,DIRECT
    - DOMAIN-SUFFIX,sciencedirect.com,DIRECT
    - DOMAIN-SUFFIX,iresearchbook.cn,DIRECT
    - DOMAIN-SUFFIX,elsevier.com,DIRECT
    - DOMAIN-SUFFIX,nature.com,DIRECT
    - DOMAIN-SUFFIX,webofknowledge.com,DIRECT
    - DOMAIN-SUFFIX,pubs.acs.org,DIRECT
    - DOMAIN-SUFFIX,scitation.org,DIRECT
    - 'DOMAIN-SUFFIX,zoho.com,DIRECT'
    - 'DOMAIN-SUFFIX,1lib.cloud,DIRECT'
    - DOMAIN-SUFFIX,1lib.domains,DIRECT
    - DOMAIN-SUFFIX,1lib.education,DIRECT
    - DOMAIN-SUFFIX,1lib.eu,DIRECT
    - DOMAIN-SUFFIX,1lib.limited,DIRECT
    - DOMAIN-SUFFIX,1lib.pl,DIRECT
    - DOMAIN-SUFFIX,1lib.to,DIRECT
    - DOMAIN-SUFFIX,1lib.tw,DIRECT
    - DOMAIN-SUFFIX,2lib.org,DIRECT
    - DOMAIN-SUFFIX,3lib.net,DIRECT
    - DOMAIN-SUFFIX,aclweb.org,DIRECT
    - DOMAIN-SUFFIX,acm.org,DIRECT
    - DOMAIN-SUFFIX,acs.org,DIRECT
    - DOMAIN-SUFFIX,aiaa.org,DIRECT
    - DOMAIN-SUFFIX,aip.org,DIRECT
    - DOMAIN-SUFFIX,altmetric.com,DIRECT
    - DOMAIN-SUFFIX,amamanualofstyle.com,DIRECT
    - DOMAIN-SUFFIX,ams.org,DIRECT
    - DOMAIN-SUFFIX,analytictech.com,DIRECT
    - DOMAIN-SUFFIX,anb.org,DIRECT,DIRECT
    - DOMAIN-SUFFIX,annualreviews.org,DIRECT
    - DOMAIN-SUFFIX,apa.org,DIRECT
    - DOMAIN-SUFFIX,apress.com,DIRECT
    - DOMAIN-SUFFIX,aps.org,DIRECT
    - DOMAIN-SUFFIX,art1lib.com,DIRECT
    - DOMAIN-SUFFIX,arxiv.org,DIRECT
    - DOMAIN-SUFFIX,ascelibrary.org,DIRECT
    - DOMAIN-SUFFIX,asha.org,DIRECT
    - DOMAIN-SUFFIX,asm.org,DIRECT
    - DOMAIN-SUFFIX,asme.org,DIRECT
    - DOMAIN-SUFFIX,astm.org,DIRECT
    - DOMAIN-SUFFIX,b-ok.africa,DIRECT
    - DOMAIN-SUFFIX,b-ok.asia,DIRECT
    - DOMAIN-SUFFIX,b-ok.cc,DIRECT
    - DOMAIN-SUFFIX,b-ok.global,DIRECT
    - DOMAIN-SUFFIX,b-ok.org,DIRECT
    - DOMAIN-SUFFIX,berkeley.edu,DIRECT
    - DOMAIN-SUFFIX,biomedcentral.com,DIRECT
    - DOMAIN-SUFFIX,biorxiv.org,DIRECT
    - DOMAIN-SUFFIX,blackstonespoliceservice.com,DIRECT
    - DOMAIN-SUFFIX,blackwell-synergy.com,DIRECT
    - DOMAIN-SUFFIX,bmj.com,DIRECT
    - DOMAIN-SUFFIX,book4you.org,DIRECT
    - DOMAIN-SUFFIX,bookfi.net,DIRECT
    - DOMAIN-SUFFIX,booksc.eu,DIRECT
    - DOMAIN-SUFFIX,booksc.me,DIRECT
    - DOMAIN-SUFFIX,booksc.org,DIRECT
    - DOMAIN-SUFFIX,booksc.xyz,DIRECT
    - DOMAIN-SUFFIX,bookshome.info,DIRECT
    - DOMAIN-SUFFIX,bookshome.net,DIRECT
    - DOMAIN-SUFFIX,bookshome.world,DIRECT
    - DOMAIN-SUFFIX,brill.com,DIRECT
    - DOMAIN-SUFFIX,cabdirect.org,DIRECT
    - DOMAIN-SUFFIX,cambridge.org,DIRECT
    - DOMAIN-SUFFIX,cambridgedigital.net,DIRECT
    - DOMAIN-SUFFIX,cambridgemaths.org,DIRECT
    - DOMAIN-SUFFIX,cambridgeschoolshakespeare.com,DIRECT
    - DOMAIN-SUFFIX,cas.org,DIRECT
    - DOMAIN-SUFFIX,cell.com,DIRECT
    - DOMAIN-SUFFIX,clarivate.com,DIRECT
    - DOMAIN-SUFFIX,cnki.net,DIRECT
    - DOMAIN-SUFFIX,computingreviews.com,DIRECT
    - DOMAIN-SUFFIX,cqvip.com,DIRECT
    - DOMAIN-SUFFIX,crossref.org,DIRECT
    - DOMAIN-SUFFIX,csiro.au,DIRECT
    - DOMAIN-SUFFIX,de1lib.org,DIRECT
    - DOMAIN-SUFFIX,deepdyve.com,DIRECT
    - DOMAIN-SUFFIX,degruyter.com,DIRECT
    - DOMAIN-SUFFIX,dentalhypotheses.com,DIRECT
    - DOMAIN-SUFFIX,doi.info,DIRECT
    - DOMAIN-SUFFIX,doi.org,DIRECT
    - DOMAIN-SUFFIX,ebscohost.com,DIRECT
    - DOMAIN-SUFFIX,elifesciences.org,DIRECT
    - DOMAIN-SUFFIX,els-cdn.com,DIRECT
    - DOMAIN-SUFFIX,elsevier-ae.com,DIRECT
    - DOMAIN-SUFFIX,elsevier.com,DIRECT
    - DOMAIN-SUFFIX,elsevier.io,DIRECT
    - DOMAIN-SUFFIX,emerald.com,DIRECT
    - DOMAIN-SUFFIX,endnote.com,DIRECT
    - DOMAIN-SUFFIX,engineeringvillage.com,DIRECT
    - DOMAIN-SUFFIX,epigeum.com,DIRECT
    - DOMAIN-SUFFIX,europepmc.org,DIRECT
    - DOMAIN-SUFFIX,evise.com,DIRECT
    - DOMAIN-SUFFIX,frontiersin.org,DIRECT
    - DOMAIN-SUFFIX,gale.com,DIRECT
    - DOMAIN-SUFFIX,galegroup.com,DIRECT
    - DOMAIN-SUFFIX,ggsrv.com,DIRECT
    - DOMAIN-SUFFIX,hindawi.com,DIRECT
    - DOMAIN-SUFFIX,hk1lib.org,DIRECT
    - DOMAIN-SUFFIX,ic.ac.uk,DIRECT
    - DOMAIN-SUFFIX,icevirtuallibrary.com,DIRECT
    - DOMAIN-SUFFIX,ieee.org,DIRECT
    - DOMAIN-SUFFIX,imf.org,DIRECT
    - DOMAIN-SUFFIX,imperial.ac.uk,DIRECT
    - DOMAIN-SUFFIX,imperial.insendi.com,DIRECT
    - DOMAIN-SUFFIX,imperialbusiness.school,DIRECT
    - DOMAIN-SUFFIX,informs.org,DIRECT
    - DOMAIN-SUFFIX,iop.org,DIRECT
    - DOMAIN-SUFFIX,isca-speech.org,DIRECT
    - DOMAIN-SUFFIX,isiknowledge.com,DIRECT
    - DOMAIN-SUFFIX,jamanetwork.com,DIRECT
    - DOMAIN-SUFFIX,japanknowledge.com,DIRECT
    - DOMAIN-SUFFIX,jbc.org,DIRECT
    - DOMAIN-SUFFIX,jbe-platform.com,DIRECT
    - DOMAIN-SUFFIX,jhu.edu,DIRECT
    - DOMAIN-SUFFIX,jmlr.org,DIRECT
    - DOMAIN-SUFFIX,jneurosci.org,DIRECT
    - DOMAIN-SUFFIX,jstor.org,DIRECT
    - DOMAIN-SUFFIX,karger.com,DIRECT
    - DOMAIN-SUFFIX,knovel.com,DIRECT
    - DOMAIN-SUFFIX,kuke.com,DIRECT
    - DOMAIN-SUFFIX,lawdata.com.tw,DIRECT
    - DOMAIN-SUFFIX,libguides.com,DIRECT
    - DOMAIN-SUFFIX,libsolutions.app,DIRECT
    - DOMAIN-SUFFIX,libsolutions.domains,DIRECT
    - DOMAIN-SUFFIX,libsolutions.net,DIRECT
    - DOMAIN-SUFFIX,liebertpub.com,DIRECT
    - DOMAIN-SUFFIX,literatumonline.com,DIRECT
    - DOMAIN-SUFFIX,ma1lib.org,DIRECT
    - DOMAIN-SUFFIX,madsrevolution.net,DIRECT
    - DOMAIN-SUFFIX,mdpi.com,DIRECT
    - DOMAIN-SUFFIX,mit,DIRECT
    - DOMAIN-SUFFIX,mit.edu,DIRECT
    - DOMAIN-SUFFIX,mit.net,DIRECT
    - DOMAIN-SUFFIX,mitpressjournals.org,DIRECT
    - DOMAIN-SUFFIX,mpg.de,DIRECT
    - DOMAIN-SUFFIX,myilibrary.com,DIRECT
    - DOMAIN-SUFFIX,nature.com,DIRECT
    - DOMAIN-SUFFIX,ncbi.nlm.nih.gov,DIRECT
    - DOMAIN-SUFFIX,nejm.org,DIRECT
    - DOMAIN-SUFFIX,neurology.org,DIRECT
    - DOMAIN-SUFFIX,newisiknowledge.com,DIRECT
    - DOMAIN-SUFFIX,oecd-ilibrary.org,DIRECT
    - DOMAIN-SUFFIX,oed.com,DIRECT
    - DOMAIN-SUFFIX,omscr.com,DIRECT
    - DOMAIN-SUFFIX,osapublishing.org,DIRECT
    - DOMAIN-SUFFIX,oup.com,DIRECT
    - DOMAIN-SUFFIX,ouplaw.com,DIRECT
    - DOMAIN-SUFFIX,ovid.com,DIRECT
    - DOMAIN-SUFFIX,ox.ac.uk,DIRECT
    - DOMAIN-SUFFIX,oxfordaasc.com,DIRECT
    - DOMAIN-SUFFIX,oxfordartonline.com,DIRECT
    - DOMAIN-SUFFIX,oxfordbibliographies.com,DIRECT
    - DOMAIN-SUFFIX,oxfordclinicalpsych.com,DIRECT
    - DOMAIN-SUFFIX,oxforddnb.com,DIRECT
    - DOMAIN-SUFFIX,oxfordfirstsource.com,DIRECT
    - DOMAIN-SUFFIX,oxfordhandbooks.com,DIRECT
    - DOMAIN-SUFFIX,oxfordlawtrove.com,DIRECT
    - DOMAIN-SUFFIX,oxfordmedicine.com,DIRECT
    - DOMAIN-SUFFIX,oxfordmusiconline.com,DIRECT
    - DOMAIN-SUFFIX,oxfordpoliticstrove.com,DIRECT
    - DOMAIN-SUFFIX,oxfordre.com,DIRECT
    - DOMAIN-SUFFIX,oxfordreference.com,DIRECT
    - DOMAIN-SUFFIX,oxfordscholarlyeditions.com,DIRECT
    - DOMAIN-SUFFIX,oxfordscholarship.com,DIRECT
    - DOMAIN-SUFFIX,oxfordwesternmusic.com,DIRECT
    - DOMAIN-SUFFIX,peerj.com,DIRECT
    - DOMAIN-SUFFIX,physiology.org,DIRECT
    - DOMAIN-SUFFIX,pkulaw.com,DIRECT
    - DOMAIN-SUFFIX,plos.org,DIRECT
    - DOMAIN-SUFFIX,pnas.org,DIRECT
    - DOMAIN-SUFFIX,princeton.edu,DIRECT
    - DOMAIN-SUFFIX,proquest.com,DIRECT
    - DOMAIN-SUFFIX,psyccareers.com,DIRECT
    - DOMAIN-SUFFIX,readcube.com,DIRECT
    - DOMAIN-SUFFIX,researchgate.net,DIRECT
    - DOMAIN-SUFFIX,routledgehandbooks.com,DIRECT
    - DOMAIN-SUFFIX,royalsocietypublishing.org,DIRECT
    - DOMAIN-SUFFIX,rsc.org,DIRECT
    - DOMAIN-SUFFIX,sagepub.com,DIRECT
    - DOMAIN-SUFFIX,scholarpedia.org,DIRECT
    - DOMAIN-SUFFIX,sci-hub.tw,DIRECT
    - DOMAIN-SUFFIX,science.org,DIRECT
    - DOMAIN-SUFFIX,sciencedirect.com,DIRECT
    - DOMAIN-SUFFIX,sciencedirectassets.com,DIRECT
    - DOMAIN-SUFFIX,sciencemag.org,DIRECT
    - DOMAIN-SUFFIX,sciencenets.com,DIRECT
    - DOMAIN-SUFFIX,scientificamerican.com,DIRECT
    - DOMAIN-SUFFIX,scitation.org,DIRECT
    - DOMAIN-SUFFIX,scopus.com,DIRECT
    - DOMAIN-SUFFIX,semanticscholar.org,DIRECT
    - DOMAIN-SUFFIX,serialssolutions.com,DIRECT
    - DOMAIN-SUFFIX,sg1lib.org,DIRECT
    - DOMAIN-SUFFIX,siam.org,DIRECT
    - DOMAIN-SUFFIX,silverchair-cdn.com,DIRECT
    - DOMAIN-SUFFIX,singlelogin.app,DIRECT
    - DOMAIN-SUFFIX,singlelogin.me,DIRECT
    - DOMAIN-SUFFIX,sipriyearbook.org,DIRECT
    - DOMAIN-SUFFIX,spiedigitallibrary.org,DIRECT
    - DOMAIN-SUFFIX,springer.com,DIRECT
    - DOMAIN-SUFFIX,springerlink.com,DIRECT
    - DOMAIN-SUFFIX,springernature.com,DIRECT
    - DOMAIN-SUFFIX,statsmakemecry.com,DIRECT
    - DOMAIN-SUFFIX,tandf.co.uk,DIRECT
    - DOMAIN-SUFFIX,tandfonline.com,DIRECT
    - DOMAIN-SUFFIX,taylorandfrancis.com,DIRECT
    - DOMAIN-SUFFIX,taylorfrancis.com,DIRECT
    - DOMAIN-SUFFIX,thelancet.com,DIRECT
    - DOMAIN-SUFFIX,turnitin.com,DIRECT
    - DOMAIN-SUFFIX,uchicago.edu,DIRECT
    - DOMAIN-SUFFIX,ucla.edu,DIRECT
    - DOMAIN-SUFFIX,ukwhoswho.com,DIRECT
    - DOMAIN-SUFFIX,umass.edu,DIRECT
    - DOMAIN-SUFFIX,un.org,DIRECT
    - DOMAIN-SUFFIX,uni-bielefeld.de,DIRECT
    - DOMAIN-SUFFIX,universitypressscholarship.com,DIRECT
    - DOMAIN-SUFFIX,uq.edu.au,DIRECT
    - DOMAIN-SUFFIX,uq.h5p.com,DIRECT
    - DOMAIN-SUFFIX,veryshortintroductions.com,DIRECT
    - DOMAIN-SUFFIX,wanfangdata.com,DIRECT
    - DOMAIN-SUFFIX,wanfangdata.com.cn,DIRECT
    - DOMAIN-SUFFIX,webofknowledge.com,DIRECT
    - DOMAIN-SUFFIX,webofscience.com,DIRECT
    - DOMAIN-SUFFIX,westlaw.com,DIRECT
    - DOMAIN-SUFFIX,westlawchina.com,DIRECT
    - DOMAIN-SUFFIX,wiley.com,DIRECT
    - DOMAIN-SUFFIX,wkap.nl,DIRECT
    - DOMAIN-SUFFIX,worldbank.org,DIRECT
    - DOMAIN-SUFFIX,worldscientific.com,DIRECT
    - DOMAIN-SUFFIX,yale.edu,DIRECT
    - DOMAIN-SUFFIX,z-lib.org,DIRECT
    - DOMAIN-SUFFIX,zlib.life,DIRECT
    - DOMAIN-SUFFIX,zlibcdn.com,DIRECT
    - DOMAIN-SUFFIX,zlibcdn2.com,DIRECT
    - DOMAIN-SUFFIX,zotero.org,DIRECT

```