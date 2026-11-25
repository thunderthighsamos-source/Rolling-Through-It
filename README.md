# Rolling-Through-It
Lg[Oven]a4a8a
Delivered-To: matthewshannonamos01@gmail.com
Received: by 2002:a05:6a20:21c2:b0:3fc:5f82:7632 with SMTP id p2csp5638959pzb; Wed, 25 Nov 2026 05:14:53 -0800 (PST)
X-Received: by 2002:a17:903:1a06:b0:2e9:8202:5083 with SMTP id d9443c01a7336-2f03f181800mr148527255ad.55.1795612493564; Wed, 25 Nov 2026 05:14:53 -0800 (PST)
ARC-Seal: i=1; a=rsa-sha256; t=1795612493; cv=none; d=google.com; s=arc-20260327; b=A9F7TjEtXYgn0sTFndQyqQAQ7m6g74f6muG1YKKuYVAOSF584oH+fRZ8VjO3+0wO3C TAErAj7HvygJ6IiTSyQ5gBoUur2/sE8FldkY7U1YABoADv6hbxs5VEjNXjAAOlatpr6s Uc3jjnKX6GaYNEfyr3mctBCeETPQQTQfwb9pstitawYWwSg8Gydg9T0iUm4RsPsYYcyA GX6+lwd/YFpaEUokMMWI7bZQVSOAuX+oLMMhIgEmHOG9taTdIi/z+fa2Th8g0Q+SfguA G2vwepgtmCio5Kk0IXy/GLkAtYRhD5xAZExysIHHD3ZbR8DAuW57bbotFUJowHi7N7rm bnUA==
ARC-Message-Signature: i=1; a=rsa-sha256; c=relaxed/relaxed; d=google.com; s=arc-20260327; h=feedback-id:reply-to:message-id:date:subject:to:from:mime-version :dkim-signature:dkim-signature; bh=JAgl5YIaNKflDESX2WwSqu4TFbrmOkOrZQV7bE93CzY=; fh=d0fmGuogqR0LlN8zMJnuBmlPVzmR0ECU7aauUumk8Go=; b=H7A8ws5nDyaBq1A33iYm4V5KR9bjFGYJiKaiT4OzVyDTCJUCMTCdHgrC0GGvb6upGM s80n8te6iusn4ZwGc+A0MWNSSeT5qol1Ijl727vy5vm0RVsuJttromCM1KiVIvgxhMOp eC2i4QMCyv+i4bFDUEyIzZd3/ivS3M4kVUq3KlD8eWsceSyhqHE52noshiYC+IfvEid3 sH9eFzyHitgvIaLAQbiJbFo+aNI64lgSCoejbvm7Ih4om3HUlR1xDqFZPbJrVTTqkCL3 Q7/VijG9YdVkKUpBPOAB8xuEDKpJL4TGiQ5mEgfDKMclptOAPuaQZfSeS1C6KlU8PtEh +baA==; dara=google.com
ARC-Authentication-Results: i=1; mx.google.com; dkim=pass header.i=@txn.dropbox.com header.s=nxegnu6u23odz4ufcwgkgjjdr3eu4rmo header.b=scKFW+z2; dkim=pass header.i=@amazonses.com header.s=hsbnp7p3ensaochzwyq5wwmceodymuwv header.b=xF4HiN3P; spf=pass (google.com: domain of 010101a212d84588-180a3d42-f84c-4e8e-b87e-6702b6800abd-000000@mail.txn.dropbox.com designates 76.223.145.126 as permitted sender) smtp.mailfrom=010101a212d84588-180a3d42-f84c-4e8e-b87e-6702b6800abd-000000@mail.txn.dropbox.com; dmarc=pass (p=REJECT sp=REJECT dis=NONE) header.from=dropbox.com
Return-Path: <010101a212d84588-180a3d42-f84c-4e8e-b87e-6702b6800abd-000000@mail.txn.dropbox.com>
Received: from c145-126.smtp-out.us-west-2.amazonses.com (c145-126.smtp-out.us-west-2.amazonses.com. [76.223.145.126]) by mx.google.com with ESMTPS id d9443c01a7336-2f03f18a439si369963515ad.122.2026.11.25.05.14.53 for <matthewshannonamos01@gmail.com> (version=TLS1_3 cipher=TLS_AES_128_GCM_SHA256 bits=128/128); Wed, 25 Nov 2026 05:14:53 -0800 (PST)
Received-SPF: pass (google.com: domain of 010101a212d84588-180a3d42-f84c-4e8e-b87e-6702b6800abd-000000@mail.txn.dropbox.com designates 76.223.145.126 as permitted sender) client-ip=76.223.145.126;
Authentication-Results: mx.google.com; dkim=pass header.i=@txn.dropbox.com header.s=nxegnu6u23odz4ufcwgkgjjdr3eu4rmo header.b=scKFW+z2; dkim=pass header.i=@amazonses.com header.s=hsbnp7p3ensaochzwyq5wwmceodymuwv header.b=xF4HiN3P; spf=pass (google.com: domain of 010101a212d84588-180a3d42-f84c-4e8e-b87e-6702b6800abd-000000@mail.txn.dropbox.com designates 76.223.145.126 as permitted sender) smtp.mailfrom=010101a212d84588-180a3d42-f84c-4e8e-b87e-6702b6800abd-000000@mail.txn.dropbox.com; dmarc=pass (p=REJECT sp=REJECT dis=NONE) header.from=dropbox.com
DKIM-Signature: v=1; a=rsa-sha256; q=dns/txt; c=relaxed/simple; s=nxegnu6u23odz4ufcwgkgjjdr3eu4rmo; d=txn.dropbox.com; t=1795612493; h=Content-Type:MIME-Version:From:To:Subject:Date:Message-ID:Reply-To; bh=aHJ0I0ZeqBGAUtqed3M+l8dT4sVD3vFV/Lkl/NhXRkE=; b=scKFW+z2JoPRywYbNLrqpckD599ukXvrVrX/OsZTtcz4BWkJSp9BkTSjrFtqh4tV 2rDFqxPjeHNuDADs7iUYX54A1jKg4P15wTqtvuLhlfp1mfAyBI0FdKJiS0y88A4J+to Vu90WDMdz1flbpY5zp0l3ZiFOYIZAWVteaoISDnU=
DKIM-Signature: v=1; a=rsa-sha256; q=dns/txt; c=relaxed/simple; s=hsbnp7p3ensaochzwyq5wwmceodymuwv; d=amazonses.com; t=1795612493; h=Content-Type:MIME-Version:From:To:Subject:Date:Message-ID:Reply-To:Feedback-ID; bh=aHJ0I0ZeqBGAUtqed3M+l8dT4sVD3vFV/Lkl/NhXRkE=; b=xF4HiN3PBr/G2+kQFA3+o/BtoaeJ/rQwsRwjm4YTuJxqy92wsmD+ea6UQ0BZCbQa 3bXSGvejMs6oDxUILQvWyW1NLcqzQdATjonc6vW1LDBVzrO3iTskLcRODCI8BWaZana NH7ahCFgsEFS1MF3VQlzMrIoPLrzsBdzFyEvr6XU=
Content-Type: multipart/alternative; boundary="===============7549808131832588495=="
MIME-Version: 1.0
From: "Matthew Shannon Amos Amos (via Dropbox)" <no-reply@txn.dropbox.com>
To: matthewshannonamos01@gmail.com
Subject: =?utf-8?q?Matthew_Shannon_Amos_Amos_shared_=22Screenshot=5F20261125=5F091316=5FTuta=2Ejpg=22_with_you?=
Date: Wed, 25 Nov 2026 13:14:53 +0000
Message-ID: <010101a212d84588-180a3d42-f84c-4e8e-b87e-6702b6800abd-000000@us-west-2.amazonses.com>
X-Dropbox-Message-ID: 75252f41b57f47e588f52d03202efe0b
Reply-To: no-reply@txn.dropbox.com
X-Auto-Response-Suppress: All
X-Dbx-iterable-msgBusID: 75252f41b57f47e588f52d03202efe0b
X-Dbx-iterable-campaignID: 19504419
X-Dbx-iterable-projectID: 12274
X-Dbx-iterable-env: prod
X-Dbx-iterable-triggerID: 2df8a6bc-23b0-4f13-a973-d058276a40f6
x-cid: 19504419
Feedback-ID: 19504419::1.us-west-2.C1J9pRCK9rJULWC8wBKFbk8/mhlW6tSneJoML9ymcSA=:AmazonSES
X-SES-Outgoing: 2026.11.25-76.223.145.126

--===============7549808131832588495==
Content-Type: text/plain; charset="utf-8"
MIME-Version: 1.0
Content-Transfer-Encoding: quoted-printable

Matthew Shannon Amos Amos (sean.chodum.burns@gmail.com) shared Screenshot_2=
0261125_091316_Tuta.jpg with you


Open: <https://www.dropbox.com/scl/fi/qi7u7pwfd53wez2u017ep/Screenshot_2026=
1125_091316_Tuta.jpg?r=3DACw0907spK1cpHkC--7OG7o-ZIh_QpVo6jLxuQwDavvnCVYImw=
JWX_p6MpBWhvfU_idnncOowzqEiE6_mLMhSFa20BapOvqUjU_stlu68dekrRBWn-SC9Q-71aqNR=
Dlxt5u1jYnE2eYns9tcxiFhoETUZAlLLGb2rxAfTqdyvGYv10OnFFyj6JrDYQrSEaVUY_H7_bSZ=
fpDCPosvjje5cplFGc-vCc0BMTAf20wJdIRlLw&sm=3D1&dl=3D0>



Included: None


Access: Can view

Size: 455 KB



Dropbox
https://www.dropbox.com
--===============7549808131832588495==
Content-Type: text/html; charset="utf-8"
MIME-Version: 1.0
Content-Transfer-Encoding: quoted-printable

<!DOCTYPE html>

<html lang=3D"en" style=3D"box-sizing: border-box;" xmlns:o=3D"urn:schemas-=
microsoft-com:office:office" xmlns:v=3D"urn:schemas-microsoft-com:vml"> <he=
ad> <title> </title> <meta content=3D"text/html; charset=3Dutf-8" http-equi=
v=3D"Content-Type"/> <meta content=3D"width=3Ddevice-width,initial-scale=3D=
1" name=3D"viewport"/> <!--[if mso]><xml> <w:worddocument xmlns:w=3D"urn:sc=
hemas-microsoft-com:office:word"> <w:dontuseadvancedtypographyreadingmail><=
/w:dontuseadvancedtypographyreadingmail> </w:worddocument> <o:officedocumen=
tsettings> <o:pixelsperinch>96</o:pixelsperinch> <o:allowpng></o:allowpng> =
</o:officedocumentsettings> </xml><![endif]--> <!--[if !mso]><!--> <style t=
ype=3D"text/css">@font-face{font-family:'Atlas Grotesk';font-style:normal;f=
ont-weight:400;font-display:swap;src:url('https://cfl.dropboxstatic.com/sta=
tic/fonts/paper-atlasgrotesk/AtlasGrotesk-Regular-Web.woff2') format('woff2=
'),url('https://cfl.dropboxstatic.com/static/fonts/paper-atlasgrotesk/Atlas=
Grotesk-Regular-Web.woff') format('woff')}@font-face{font-family:'Atlas Gro=
tesk';font-style:normal;font-weight:500;font-display:swap;src:url('https://=
cfl.dropboxstatic.com/static/fonts/paper-atlasgrotesk/AtlasGrotesk-Medium-W=
eb.woff2') format('woff2'),url('https://cfl.dropboxstatic.com/static/fonts/=
paper-atlasgrotesk/AtlasGrotesk-Medium-Web.woff') format('woff')}</style> <=
!--<![endif]--> <style>*{box-sizing:border-box}body{margin:0;padding:0}a[x-=
apple-data-detectors]{color:inherit!important;text-decoration:inherit!impor=
tant}.header-email,.header-email a,.header-email a:link,.header-email a:vis=
ited{color:#1e1919!important;text-decoration:none!important;font:inherit!im=
portant}#MessageViewBody a{color:inherit;text-decoration:none}p{line-height=
:inherit}.desktop_hide,.desktop_hide table{mso-hide:all;display:none;max-he=
ight:0;overflow:hidden}.image_block img+div{display:none}sub,sup{font-size:=
75%;line-height:0}.row-15 .column{padding-top:0!important;padding-bottom:0!=
important}.row-15 .text_block.block-1 td.pad{padding-top:3px!important}@med=
ia(max-width:520px){.row-content{width:100%!important}.stack .column{width:=
100%!important;display:block}.mobile_hide{min-height:0;max-height:0;max-wid=
th:0;display:none;overflow:hidden;font-size:0}.desktop_hide,.desktop_hide t=
able{display:table!important;max-height:none!important}.row-1 .column-2 .bl=
ock-2.text_block td.pad{padding:20px 10px 20px 0!important}.row-17 .column-=
2 .block-3.spacer_block{height:40px!important}.row-17 .column-2 .block-6.sp=
acer_block{height:45px!important}.row-17 .column-1 .block-2.spacer_block,.r=
ow-17 .column-1 .block-4.spacer_block{height:25px!important}.row-17 .column=
-2 .block-1.text_block td.pad,.row-17 .column-2 .block-2.text_block td.pad,=
.row-17 .column-2 .block-4.text_block td.pad,.row-17 .column-2 .block-5.tex=
t_block td.pad,.row-17 .column-2 .block-7.text_block td.pad,.row-17 .column=
-2 .block-8.text_block td.pad{padding:5px 10px 0 20px!important}.row-4 .col=
umn-1 .block-1.image_block .pad>div,.row-4 .column-1 .block-1.image_block i=
mg.preview-image{height:211px!important}.row-4 .column-2 .block-1.image_blo=
ck .pad>div,.row-4 .column-2 .block-1.image_block img.preview-image{height:=
119px!important}.row-4 .column-2 .block-2.image_block .pad>div,.row-4 .colu=
mn-2 .block-2.image_block img.preview-image{height:80px!important}}</style>=
 <!--[if mso ]><style>sup,sub{font-size:100%!important}sup{mso-text-raise:1=
0%}sub{mso-text-raise:-10%}</style><![endif]--> <style type=3D"text/css">.i=
b-email-footer,.ib-email-footer table,.ib-email-footer td{background-color:=
#f1f2f4!important}</style> <!-- mobile-fallback-centering --> <style type=
=3D"text/css">@media(max-width:520px){.row-4 .column-1 .block-1.image_block=
 .pad>div.fallback-cell{height:211px!important}.row-4 .column-2 .block-1.im=
age_block .pad>div.fallback-cell{height:119px!important}.row-4 .column-2 .b=
lock-2.image_block .pad>div.fallback-cell{height:80px!important}.fallback-c=
ell>a{height:100%!important}.fallback-icon{height:55px!important;width:55px=
!important}.fallback-extension{font-size:13px!important;line-height:18px!im=
portant}.row-7 .column-1 .block-1.image_block .pad>div,.row-7 .column-1 .bl=
ock-1.image_block img.preview-image,.row-7 .column-2 .block-1.image_block .=
pad>div,.row-7 .column-2 .block-1.image_block img.preview-image{height:211p=
x!important}.row-9 .column-1 .block-1.image_block .pad>div.single-image-pre=
view,.row-9 .column-1 .block-1.image_block img.single-image-preview-image{h=
eight:211px!important}.row-9 .column-1 .block-1.image_block .pad>div.restri=
cted-preview,.row-9 .column-1 .block-1.image_block img.restricted-preview-i=
mage{height:147px!important}}</style> </head> <body class=3D"body" style=3D=
"box-sizing: border-box; margin: 0; padding: 0; -webkit-text-size-adjust: n=
one; text-size-adjust: none; background-color: #fff;"><span style=3D"color:=
transparent;visibility:hidden;display:none;opacity:0;height:0;width:0;font-=
size:0;">https://www.<span>dropbox</span>.com/scl/fi/qi7u7pwfd53wez2u017ep/=
Screenshot_20261125_091316_<span>Tuta</span>.jpg?rlkey=3Dztn23y7axbdoh4jzay=
1v03pv5&amp;st=3Dndbk8fwg&amp;dl=3D0</span><img height=3D"1" src=3D"https:/=
/links.dropbox.com/e/eo?_t=3D60154b197d654466a40480a2b908d3b7&amp;_m=3D7525=
2f41b57f47e588f52d03202efe0b&amp;_e=3D_jFaPVYqJBlnOnCmWAcc1SMKuMvsqi7TD_r0E=
dT9cgU1I0HTA_IInrZ-b0kjSR7q655aufGNX8eGFlqFaPGfBi1ztRDnRMl-sERwMA5C42H0BGVC=
c0t3jpBASD682VGNUY1is4PILVKaidcattkiICd8WwxiDNZEIOuZnfZXd8U%3D&amp;dbx_camp=
id=3D19504419" style=3D"border:0;width:1px;height:1px;border-width:0px!impo=
rtant;display:none!important;line-height:0!important;" width=3D"1"/> <table=
 bgcolor=3D"#fff" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D=
"nl-container" role=3D"presentation" style=3D"box-sizing: border-box; mso-t=
able-lspace: 0; mso-table-rspace: 0; background-color: #fff;" width=3D"100%=
"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: borde=
r-box;"> <td style=3D"box-sizing: border-box;"> <table align=3D"center" bor=
der=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row row-1" role=3D"p=
resentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-tabl=
e-rspace: 0;" width=3D"100%"> <tbody style=3D"box-sizing: border-box;"> <tr=
 style=3D"box-sizing: border-box;"> <td style=3D"box-sizing: border-box;"> =
<table align=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" cl=
ass=3D"row-content" role=3D"presentation" style=3D"box-sizing: border-box; =
mso-table-lspace: 0; mso-table-rspace: 0; border-radius: 0; color: #000; wi=
dth: 500px; margin: 0 auto;" width=3D"500"> <tbody style=3D"box-sizing: bor=
der-box;"> <tr style=3D"box-sizing: border-box;"> <td align=3D"left" class=
=3D"column column-1" style=3D"box-sizing: border-box; mso-table-lspace: 0; =
mso-table-rspace: 0; font-weight: 400; text-align: left; padding-bottom: 15=
px; padding-top: 15px; vertical-align: middle; width: 44px;" valign=3D"midd=
le" width=3D"44"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" c=
lass=3D"image_block mobile_hide block-1" role=3D"presentation" style=3D"box=
-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"10=
0%"> <tr style=3D"box-sizing: border-box;"> <td align=3D"left" class=3D"pad=
" style=3D"box-sizing: border-box; width: 100%;" width=3D"100%"> <div style=
=3D"box-sizing: border-box; max-width: 44px;"> <a href=3D"https://links.dro=
pbox.com/u/click?_t=3D60154b197d654466a40480a2b908d3b7&amp;_m=3D75252f41b57=
f47e588f52d03202efe0b&amp;_e=3DhH3WD5o0NxcWyIebdX1AE-sDN8SKtQJMOdYLhfzqfde4=
YX4mOBQEixuVQENsoxzImukIK3zoxtvyg3AqWk0K4IWPLzx9neNtA3vhZBpxcNRrdy8L5T0gBKR=
8MuiZ49FUUBiZHfidzAC5TsgzSGvPSsY33EgbVfbty8QrZJEXU_evkiM-f6g_5mjDO-XQ1em2M_=
2TpSIgxCvSg6MQVktLhihaBqHC62M751TZjphHNBNEJROm5JnhJ8MC-so-D4yJC221QwWsGLVqy=
U52dipbixsqUT4L8VXJBuSGaaayi-qKOPwI701ssYnOdLbprjdDjpkFyx9I8ux5KHOQW6l4giGX=
I3A_aKj00Owz34_vchC7dpQy4ElEZ83RFlKGaDYFI9hGpXFFSattcHU1_w234uCY7LI0uXhpB5T=
lqMA2F_I%3D&amp;dbx_campid=3D19504419&amp;dbx_src=3Demail&amp;dbx_track=3DA=
AM2nbgyjrRwhkRY54d1SHPwtE9XJ0ystvuT8K5Owf-mtdKLa9BOvk45boTOTTJODCFz5f_SO-EB=
hbO4lYhylHPpzYxjzoYr1X82RtiumPuNFg" style=3D"box-sizing: border-box;" targe=
t=3D"_blank"> <img height=3D"auto" src=3D"https://library.iterable.com/2477=
/12274/fdec8a840332497499b0b6854a4a4e7d-dropbox-logo.png" style=3D"box-sizi=
ng: border-box; display: block; height: auto; border: 0; width: 100%;" titl=
e=3D"Dropbox " width=3D"44"/> </a> </div> </td> </tr> </table> <table borde=
r=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"image_block desktop_hi=
de block-2" role=3D"presentation" style=3D"box-sizing: border-box; mso-tabl=
e-lspace: 0; mso-table-rspace: 0; mso-hide: all; display: none; max-height:=
 0; overflow: hidden;" width=3D"100%"> <tr style=3D"box-sizing: border-box;=
"> <td align=3D"left" class=3D"pad" style=3D"box-sizing: border-box; width:=
 100%;" width=3D"100%"> <div style=3D"box-sizing: border-box; max-width: 44=
px;"> <a href=3D"https://links.dropbox.com/u/click?_t=3D60154b197d654466a40=
480a2b908d3b7&amp;_m=3D75252f41b57f47e588f52d03202efe0b&amp;_e=3DhH3WD5o0Nx=
cWyIebdX1AE-sDN8SKtQJMOdYLhfzqfde4YX4mOBQEixuVQENsoxzImukIK3zoxtvyg3AqWk0K4=
IWPLzx9neNtA3vhZBpxcNRrdy8L5T0gBKR8MuiZ49FUUBiZHfidzAC5TsgzSGvPSlp_igfamonp=
lMek-yg2aMK1knAi2LpoM-QqQ1eRII57sMGN-sl5MkAyykT1sV1QRq9M_oZOw4JxW4sNH5Xc4uN=
UPy8WbGbMmnjaCaAcsV6yC59YrcwLDx6u476u8R76Ms7CNS75M1g3gA1FgYacs6tDycMiTp1so8=
YjmkdC9w_QTib4Mu55vzxXMIi1yLmSwF-WR55m9Ve-EvYg6v3c1HEnubYhDkSKTrNI28-WQkqNB=
_0kuLrMES6CaqYx55elOMBG8WynfzbXXCIjVKI9C5Y%3D&amp;dbx_campid=3D19504419&amp=
;dbx_src=3Demail&amp;dbx_track=3DAAM2nbgyjrRwhkRY54d1SHPwtE9XJ0ystvuT8K5Owf=
-mtdKLa9BOvk45boTOTTJODCFz5f_SO-EBhbO4lYhylHPpzYxjzoYr1X82RtiumPuNFg" style=
=3D"box-sizing: border-box;" target=3D"_blank"> <img height=3D"auto" src=3D=
"https://library.iterable.com/2477/12274/fdec8a840332497499b0b6854a4a4e7d-d=
ropbox-logo.png" style=3D"box-sizing: border-box; display: block; height: a=
uto; border: 0; width: 100%;" title=3D"Dropbox " width=3D"44"/> </a> </div>=
 </td> </tr> </table> </td> <td aria-hidden=3D"true" style=3D"box-sizing: b=
order-box; width: 15px; min-width: 15px; max-width: 15px; font-size: 0; lin=
e-height: 0; mso-line-height-rule: exactly;" width=3D"15">=E2=80=8A</td> <t=
d align=3D"left" class=3D"column column-2" style=3D"box-sizing: border-box;=
 mso-table-lspace: 0; mso-table-rspace: 0; font-weight: 400; text-align: le=
ft; padding-bottom: 5px; padding-top: 5px; vertical-align: middle;" valign=
=3D"middle"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=
=3D"text_block mobile_hide block-1" role=3D"presentation" style=3D"box-sizi=
ng: border-box; mso-table-lspace: 0; mso-table-rspace: 0; word-break: break=
-word;" width=3D"100%"> <tr style=3D"box-sizing: border-box;"> <td class=3D=
"pad" style=3D"box-sizing: border-box; padding-top: 2px;"> <div style=3D"bo=
x-sizing: border-box; font-family: Arial,sans-serif;"> <div class=3D"" styl=
e=3D"box-sizing: border-box; font-size: 14px; font-family: 'Atlas Grotesk',=
-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Aria=
l,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol'; mso-li=
ne-height-alt: 21px; color: #1a1918; line-height: 1.5;"> <p style=3D"box-si=
zing: border-box; line-height: inherit; margin: 0; font-size: 14px; text-al=
ign: left; mso-line-height-alt: 30px;"> <span style=3D"box-sizing: border-b=
ox; word-break: break-word; font-size: 18px; font-weight: 500; line-height:=
 1.25;"> <span style=3D"box-sizing: border-box; word-break: break-word; col=
or: #1e1919;">Matthew Shannon Amos Amos <span class=3D"header-email" style=
=3D"box-sizing: border-box; display: inline-block; white-space: nowrap; col=
or: #1e1919!important; text-decoration: none!important; font: inherit!impor=
tant;">(sean.chodum.burns@gmail.com)</span> shared</span> <a href=3D"https:=
//www.dropbox.com/l/scl/AAPRSwzc_cq_HxkI-JeTOKy9fp2FD__mENE?dbx_campid=3D19=
504419&amp;dbx_src=3Demail" style=3D"box-sizing: border-box; color: #0061fe=
; text-decoration: none;" target=3D"_blank"><span style=3D"box-sizing: bord=
er-box; word-break: break-word; color: #0061fe;">Screenshot_20261125_091316=
_Tuta.jpg</span></a> with you</span> </p> </div> </div> </td> </tr> </table=
> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"text_blo=
ck desktop_hide block-2" role=3D"presentation" style=3D"box-sizing: border-=
box; mso-table-lspace: 0; mso-table-rspace: 0; mso-hide: all; display: none=
; max-height: 0; overflow: hidden; word-break: break-word;" width=3D"100%">=
 <tr style=3D"box-sizing: border-box;"> <td class=3D"pad" style=3D"box-sizi=
ng: border-box; padding-top: 20px; padding-bottom: 20px;"> <div style=3D"bo=
x-sizing: border-box; font-family: Arial,sans-serif;"> <div class=3D"" styl=
e=3D"box-sizing: border-box; font-size: 14px; font-family: 'Atlas Grotesk',=
-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Aria=
l,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol'; mso-li=
ne-height-alt: 21px; color: #1a1918; line-height: 1.5;"> <p style=3D"box-si=
zing: border-box; line-height: inherit; margin: 0; font-size: 14px; text-al=
ign: left; mso-line-height-alt: 30px;"> <span style=3D"box-sizing: border-b=
ox; word-break: break-word; font-size: 16px; font-weight: 500; line-height:=
 1.25;"> <span style=3D"box-sizing: border-box; word-break: break-word; col=
or: #1e1919;">Matthew Shannon Amos Amos <span class=3D"header-email" style=
=3D"box-sizing: border-box; display: inline-block; white-space: nowrap; col=
or: #1e1919!important; text-decoration: none!important; font: inherit!impor=
tant;">(sean.chodum.burns@gmail.com)</span> shared</span> <a href=3D"https:=
//www.dropbox.com/l/scl/AANMneEjzzk4vG_wUX8YYI-qXGF640PamLU?dbx_campid=3D19=
504419&amp;dbx_src=3Demail" style=3D"box-sizing: border-box; color: #0061fe=
; text-decoration: none;" target=3D"_blank"><span style=3D"box-sizing: bord=
er-box; word-break: break-word; color: #0061fe;">Screenshot_20261125_091316=
_Tuta.jpg</span></a> <span style=3D"box-sizing: border-box; word-break: bre=
ak-word; color: #1e1919;">with you</span> </span> </p> </div> </div> </td> =
</tr> </table> </td> </tr> </tbody> </table> </td> </tr> </tbody> </table> =
<table align=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" cl=
ass=3D"row row-2" role=3D"presentation" style=3D"box-sizing: border-box; ms=
o-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tbody style=3D"bo=
x-sizing: border-box;"> <tr style=3D"box-sizing: border-box;"> <td style=3D=
"box-sizing: border-box; padding-top: 18px;"> <table align=3D"center" borde=
r=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row-content stack" rol=
e=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; ms=
o-table-rspace: 0; border-radius: 16px 16px 0 0; color: #000; width: 500px;=
 margin: 0 auto;" width=3D"500"> <tbody style=3D"box-sizing: border-box;"> =
<tr style=3D"box-sizing: border-box;"> <td align=3D"left" class=3D"column c=
olumn-1" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rs=
pace: 0; font-weight: 400; text-align: left; border-left: 1px solid #d0d0d3=
; border-right: 1px solid #d0d0d3; border-top: 1px solid #d0d0d3; border-ra=
dius: 16px 16px 0 0; vertical-align: top; width: 100%;" valign=3D"top" widt=
h=3D"100%"> <div class=3D"spacer_block block-1" style=3D"box-sizing: border=
-box; height: 12px; line-height: 12px; font-size: 1px;">=E2=80=8A</div> </t=
d> </tr> </tbody> </table> </td> </tr> </tbody> </table> <table align=3D"ce=
nter" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row row-3" =
role=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0;=
 mso-table-rspace: 0;" width=3D"100%"> <tbody style=3D"box-sizing: border-b=
ox;"> <tr style=3D"box-sizing: border-box;"> <td style=3D"box-sizing: borde=
r-box;"> <table align=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=
=3D"0" class=3D"row-content stack" role=3D"presentation" style=3D"box-sizin=
g: border-box; mso-table-lspace: 0; mso-table-rspace: 0; border-radius: 0; =
color: #000; width: 500px; margin: 0 auto;" width=3D"500"> <tbody style=3D"=
box-sizing: border-box;"> <tr style=3D"box-sizing: border-box;"> <td align=
=3D"left" class=3D"column column-1" style=3D"box-sizing: border-box; mso-ta=
ble-lspace: 0; mso-table-rspace: 0; font-weight: 400; text-align: left; bor=
der-left: 1px solid #d0d0d3; border-right: 1px solid #d0d0d3; vertical-alig=
n: top; width: 100%;" valign=3D"top" width=3D"100%"> </td> </tr> </tbody> <=
/table> </td> </tr> </tbody> </table> <table align=3D"center" border=3D"0" =
cellpadding=3D"0" cellspacing=3D"0" class=3D"row row-9" role=3D"presentatio=
n" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: =
0;" width=3D"100%"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"=
box-sizing: border-box;"> <td style=3D"box-sizing: border-box;"> <table ali=
gn=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row=
-content stack" role=3D"presentation" style=3D"box-sizing: border-box; mso-=
table-lspace: 0; mso-table-rspace: 0; border-radius: 0; color: #000; width:=
 500px; margin: 0 auto;" width=3D"500"> <tbody style=3D"box-sizing: border-=
box;"> <tr style=3D"box-sizing: border-box;"> <td align=3D"left" class=3D"c=
olumn column-1" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-t=
able-rspace: 0; font-weight: 400; text-align: left; border-left: 1px solid =
#d0d0d3; border-right: 1px solid #d0d0d3; padding-bottom: 5px; padding-top:=
 5px; vertical-align: top; width: 100%;" valign=3D"top" width=3D"100%"> <ta=
ble border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"image_block b=
lock-1" role=3D"presentation" style=3D"box-sizing: border-box; mso-table-ls=
pace: 0; mso-table-rspace: 0;" width=3D"100%"> <tr style=3D"box-sizing: bor=
der-box;"> <td align=3D"center" class=3D"pad" style=3D"box-sizing: border-b=
ox; width: 100%; padding-left: 15px; padding-right: 15px;" width=3D"100%"> =
<div class=3D"single-image-preview" style=3D"box-sizing: border-box; max-wi=
dth: 570px; height: 288px;"> <a href=3D"https://www.dropbox.com/l/scl/AAOLF=
R7elr5u0eVm0dj4CZEBy-aS8w85vGI?dbx_campid=3D19504419&amp;dbx_src=3Demail" s=
tyle=3D"box-sizing: border-box; text-decoration: none; display: block; widt=
h: 100%; height: 100%;" target=3D"_blank"> <img class=3D"single-image-previ=
ew-image" height=3D"288" src=3D"https://uc936aa63627822c6f0a27fa900e.previe=
ws.dropboxusercontent.com/p/thumb/ADRRBzrUoQJNdPyTiACU53tj3rhItT7zdYidLFw6y=
nlEQpMtrp8f9wWVF0_oY8I6F6TjiHX0Axy65GYMoQDu3fCbgK2t-e-fp3cy3qCAqertES8dy5f5=
tKWSW6vz5vz1ODVC3KaJ-5q-zJWSBEvTiW0bAWC2VySiKjw6F2TDrjhmbGDEFlwmbbQzz2f5Qoy=
VGp9POb_DqjWCsWgBArUSYgPSOeJF358cZ6YDm6DFAqNZzkvaGM35HxL6Rf1nhbuFmVKqxq1SC2=
hhOCl82NEOkx9TigaTy7V9QvS1O8Ddj7hm9g/p.jpeg" style=3D"display: block; heigh=
t: 288px; object-fit: cover; border: 0.5px solid #DBDBDB; box-sizing: borde=
r-box; border-radius: 9px; width: 100%;" title=3D"" width=3D"556"/> </a> </=
div> </td> </tr> </table> </td> </tr> </tbody> </table> </td> </tr> </tbody=
> </table> <table align=3D"center" border=3D"0" cellpadding=3D"0" cellspaci=
ng=3D"0" class=3D"row row-11" role=3D"presentation" style=3D"box-sizing: bo=
rder-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tbody=
 style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: border-box;"> =
<td style=3D"box-sizing: border-box;"> <table align=3D"center" border=3D"0"=
 cellpadding=3D"0" cellspacing=3D"0" class=3D"row-content stack" role=3D"pr=
esentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table=
-rspace: 0; border-radius: 0; color: #000; width: 500px; margin: 0 auto;" w=
idth=3D"500"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-si=
zing: border-box;"> <td align=3D"left" class=3D"column column-1" style=3D"b=
ox-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; font-weigh=
t: 400; text-align: left; border-left: 1px solid #d0d0d3; border-right: 1px=
 solid #d0d0d3; padding-bottom: 5px; padding-top: 5px; vertical-align: top;=
 width: 100%;" valign=3D"top" width=3D"100%"> <div class=3D"spacer_block bl=
ock-1" style=3D"box-sizing: border-box; height: 33px; line-height: 33px; fo=
nt-size: 1px;">=E2=80=8A</div> </td> </tr> </tbody> </table> </td> </tr> </=
tbody> </table> <table align=3D"center" border=3D"0" cellpadding=3D"0" cell=
spacing=3D"0" class=3D"row row-12" role=3D"presentation" style=3D"box-sizin=
g: border-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <=
tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: border-bo=
x;"> <td style=3D"box-sizing: border-box;"> <table align=3D"center" border=
=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row-content" role=3D"pr=
esentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table=
-rspace: 0; border-radius: 0; color: #000; width: 500px; margin: 0 auto;" w=
idth=3D"500"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-si=
zing: border-box;"> <td align=3D"left" class=3D"column column-1" style=3D"b=
ox-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; font-weigh=
t: 400; text-align: left; border-left: 1px solid #d0d0d3; padding-left: 13p=
x; vertical-align: top; width: 68px;" valign=3D"top" width=3D"68"> <table b=
order=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"image_block block-=
1" role=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspace:=
 0; mso-table-rspace: 0;" width=3D"100%"> <tr style=3D"box-sizing: border-b=
ox;"> <td align=3D"left" class=3D"pad" style=3D"box-sizing: border-box; wid=
th: 100%;" width=3D"100%"> <div style=3D"box-sizing: border-box; width: 35.=
75px; height: 35.75px; max-width: 35.75px; border-radius: 50%; overflow: hi=
dden;"> <img height=3D"35.75" src=3D"https://dl-web.dropbox.com/account_pho=
to/get/pid_uphoto%3AAAAAALzJuHKb-FaIK0U2M6FhVYlKgOyWE-xJ25G0n_co-UatdLDpZtO=
5mc_B45TkbMGNnuHlHobU2K96lCqa?size=3D128x128&amp;vers=3D1771268908262" styl=
e=3D"box-sizing: border-box; display: block; width: 35.75px; height: 35.75p=
x; border: 0; border-radius: 50%; object-fit: cover;" title=3D"" width=3D"3=
5.75"/> </div> </td> </tr> </table> </td> <td align=3D"left" class=3D"colum=
n column-2" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table=
-rspace: 0; font-weight: 400; text-align: left; border-right: 1px solid #d0=
d0d3; padding-right: 13px; vertical-align: top;" valign=3D"top"> <table bor=
der=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"text_block block-1" =
role=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0;=
 mso-table-rspace: 0; word-break: break-word;" width=3D"100%"> <tr style=3D=
"box-sizing: border-box;"> <td class=3D"pad" style=3D"box-sizing: border-bo=
x;"> <div style=3D"box-sizing: border-box; font-family: Arial,sans-serif;">=
 <div class=3D"" style=3D"box-sizing: border-box; font-size: 14px; font-fam=
ily: 'Atlas Grotesk',-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica=
 Neue',Helvetica,Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Seg=
oe UI Symbol'; mso-line-height-alt: 21px; color: #1e1919; line-height: 1.5;=
"> <p style=3D"box-sizing: border-box; line-height: inherit; margin: 0; fon=
t-size: 14px; text-align: left; mso-line-height-alt: 24px; letter-spacing: =
normal;"> <span style=3D"box-sizing: border-box; word-break: break-word; fo=
nt-size: 16px; color: #1e1919;">https://www.<span>dropbox</span>.com/scl/fi=
/qi7u7pwfd53wez2u017ep/Screenshot_20261125_091316_<span>Tuta</span>.jpg?rlk=
ey=3Dztn23y7axbdoh4jzay1v03pv5&amp;st=3Dndbk8fwg&amp;dl=3D0</span> </p> </d=
iv> </div> </td> </tr> </table> </td> </tr> </tbody> </table> </td> </tr> <=
/tbody> </table><table align=3D"center" border=3D"0" cellpadding=3D"0" cell=
spacing=3D"0" class=3D"row row-13" role=3D"presentation" style=3D"box-sizin=
g: border-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <=
tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: border-bo=
x;"> <td style=3D"box-sizing: border-box;"> <table align=3D"center" border=
=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row-content stack" role=
=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso=
-table-rspace: 0; border-radius: 0; color: #000; width: 500px; margin: 0 au=
to;" width=3D"500"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"=
box-sizing: border-box;"> <td align=3D"left" class=3D"column column-1" styl=
e=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; font=
-weight: 400; text-align: left; border-left: 1px solid #d0d0d3; border-righ=
t: 1px solid #d0d0d3; vertical-align: top; width: 100%;" valign=3D"top" wid=
th=3D"100%"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=
=3D"button_block block-1" role=3D"presentation" style=3D"box-sizing: border=
-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tr style=
=3D"box-sizing: border-box;"> <td align=3D"center" class=3D"pad" style=3D"b=
ox-sizing: border-box; padding: 26px 15px 15px; font-family: -apple-system,=
BlinkMacSystemFont,'Segoe UI',Helvetica,Arial,sans-serif!important;"> <a hr=
ef=3D"https://www.dropbox.com/l/scl/AAOYojDon_0JNIre0Nz7xSfyFBCksUKm1kY?dbx=
_campid=3D19504419&amp;dbx_src=3Demail" style=3D"box-sizing: border-box; co=
lor: #ffffff; text-decoration: none; font-family: 'Atlas Grotesk',-apple-sy=
stem,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-se=
rif!important;" target=3D"_blank"> <!--[if mso]><v:roundrect arcsize=3D"20%=
" fillcolor=3D"#1e1919" href=3D"https://links.dropbox.com/u/click?_t=3D6015=
4b197d654466a40480a2b908d3b7&amp;_m=3D75252f41b57f47e588f52d03202efe0b&amp;=
_e=3DhH3WD5o0NxcWyIebdX1AE-sDN8SKtQJMOdYLhfzqfdeorCBMTCb5pBfPdNz-tdcZtJE6h-=
-gFSOlyOLaboWw_Oktmevb3SFej_FoTLYaG4IJf1nGEsafiqdOMfEQgGBELV4LerEWT0aG1jQx_=
i4la6uuK4zIbsb-5r616HOMWYp-t5Ea77tEfWx4hV_GcaBATtGfG-ssk8OlEhPZUNbV7xDfcBgR=
bpV-NqOIyzsiwhkcP0RUAFinbQj85rC67I5MBQtrboWrp8KvxF6eEH8dio3ZndX31zNnS4LOPQk=
dviibD4lQzsrsA2yqNZMvjBq9OKqekJYbtvSATIXFEc8laYqn9K7a1sjl9f2-ErZ9hmI8QGtXWg=
alTu_Wlh9hRaO61aq_KxXdgTBjKxXJLTPreYA9dXBfn_2N6xMpkQAb-JBDK_Fers0GmVptuznHl=
H_uoAIz0ycu1K2P_kH5h5KPjkzKgm_PU-R-OxsoBIsunYbt4zbGMeiXLHED6So9lig-&amp;_tr=
ggr=3Dtrue&amp;dbx_campid=3D19504419&amp;dbx_track=3DAAM2nbgyjrRwhkRY54d1SH=
PwtE9XJ0ystvuT8K5Owf-mtdKLa9BOvk45boTOTTJODCFz5f_SO-EBhbO4lYhylHPpzYxjzoYr1=
X82RtiumPuNFg" style=3D"height:46px;width:560px;v-text-anchor:middle;" xmln=
s:v=3D"urn:schemas-microsoft-com:vml" xmlns:w=3D"urn:schemas-microsoft-com:=
office:word"> <v:stroke color=3D"#1e1919" dashstyle=3D"Solid" weight=3D"0px=
"></v:stroke> <w:anchorlock></w:anchorlock> <v:textbox inset=3D"0px,0px,0px=
,0px"> <center dir=3D"false" style=3D"color:#ffffff;font-family:'Atlas Grot=
esk',-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica=
,Arial,sans-serif!important;font-size:18px"></center></v:textbox></v:roundr=
ect><![endif]--> <span class=3D"button" style=3D"box-sizing: border-box; ba=
ckground-color: #1e1919; mso-shading: transparent; border-bottom: 0px solid=
 transparent; border-left: 0px solid transparent; border-radius: 9px; borde=
r-right: 0px solid transparent; border-top: 0px solid transparent; color: #=
ffffff; display: inline-block; font-size: 18px; font-weight: 400; mso-borde=
r-alt: none; padding-bottom: 5px; padding-top: 5px; padding-left: 60px; pad=
ding-right: 60px; text-align: center; width: 100%; word-break: keep-all; le=
tter-spacing: normal; font-family: 'Atlas Grotesk',-apple-system,BlinkMacSy=
stemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif!important;"=
> <span style=3D"box-sizing: border-box; word-break: break-word; line-heigh=
t: 36px; font-family: 'Atlas Grotesk',-apple-system,BlinkMacSystemFont,'Seg=
oe UI','Helvetica Neue',Helvetica,Arial,sans-serif!important;"><font face=
=3D"Arial, Helvetica, sans-serif" style=3D"box-sizing: border-box; font-fam=
ily: -apple-system,BlinkMacSystemFont,'Segoe UI',Helvetica,Arial,sans-serif=
!important;">Open file</font></span> </span> <!--[if mso]>  <![endif]--> </=
a> </td> </tr> </table> </td> </tr> </tbody> </table> </td> </tr> </tbody> =
</table> <table align=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=
=3D"0" class=3D"row row-14" role=3D"presentation" style=3D"box-sizing: bord=
er-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tbody s=
tyle=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: border-box;"> <t=
d style=3D"box-sizing: border-box;"> <table align=3D"center" border=3D"0" c=
ellpadding=3D"0" cellspacing=3D"0" class=3D"row-content stack" role=3D"pres=
entation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-r=
space: 0; border-radius: 0; color: #000; width: 500px; margin: 0 auto;" wid=
th=3D"500"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizi=
ng: border-box;"> <td align=3D"left" class=3D"column column-1" style=3D"box=
-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; font-weight:=
 400; text-align: left; border-left: 1px solid #d0d0d3; border-right: 1px s=
olid #d0d0d3; padding-bottom: 5px; padding-top: 5px; vertical-align: top; w=
idth: 100%;" valign=3D"top" width=3D"100%"> <div class=3D"spacer_block bloc=
k-1" style=3D"box-sizing: border-box; height: 2px; line-height: 2px; font-s=
ize: 1px;">=E2=80=8A</div> </td> </tr> </tbody> </table> </td> </tr> </tbod=
y> </table> <table align=3D"center" border=3D"0" cellpadding=3D"0" cellspac=
ing=3D"0" class=3D"row row-15 mobile_hide" role=3D"presentation" style=3D"b=
ox-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"=
100%"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: b=
order-box;"> <td style=3D"box-sizing: border-box;"> <table align=3D"center"=
 border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row-content" rol=
e=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; ms=
o-table-rspace: 0; border-radius: 0; color: #000; width: 500px; margin: 0 a=
uto;" width=3D"500"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D=
"box-sizing: border-box;"> <td align=3D"left" class=3D"column column-1" sty=
le=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; fon=
t-weight: 400; text-align: left; border-left: 1px solid #d0d0d3; vertical-a=
lign: middle; width: 14%; padding-top: 0!important; padding-bottom: 0!impor=
tant;" valign=3D"middle" width=3D"14%"> <table border=3D"0" cellpadding=3D"=
0" cellspacing=3D"0" class=3D"image_block block-1" role=3D"presentation" st=
yle=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0;" w=
idth=3D"100%"> <tr style=3D"box-sizing: border-box;"> <td align=3D"right" c=
lass=3D"pad" style=3D"box-sizing: border-box; width: 100%; padding-right: 1=
2px;" width=3D"100%"> <div style=3D"box-sizing: border-box; width: 32px; he=
ight: 32px; max-width: 32px; background-color: #f7f5f2; border-radius: 8px;=
 overflow: hidden;"><img height=3D"32" src=3D"https://library.iterable.com/=
2477/12274/8ae472be2fdd4d2eb13fb1a27895b021-file-icon.png" style=3D"box-siz=
ing: border-box; display: block; height: 32px; border: 0; width: 32px;" tit=
le=3D"File Icon" width=3D"32"/></div> </td> </tr> </table> </td> <td align=
=3D"left" class=3D"column column-2" style=3D"box-sizing: border-box; mso-ta=
ble-lspace: 0; mso-table-rspace: 0; font-weight: 400; text-align: left; bor=
der-right: 1px solid #d0d0d3; padding-right: 12px; vertical-align: middle; =
width: 19.333333333333332%; padding-top: 0!important; padding-bottom: 0!imp=
ortant;" valign=3D"middle" width=3D"19.333333333333332%"> <table border=3D"=
0" cellpadding=3D"0" cellspacing=3D"0" class=3D"text_block block-1" role=3D=
"presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-ta=
ble-rspace: 0; word-break: break-word;" width=3D"100%"> <tr style=3D"box-si=
zing: border-box;"> <td class=3D"pad" style=3D"box-sizing: border-box; padd=
ing-top: 3px!important;"> <div style=3D"box-sizing: border-box; font-family=
: Arial,sans-serif;"> <div class=3D"" style=3D"box-sizing: border-box; font=
-size: 14px; font-family: 'Atlas Grotesk',-apple-system,BlinkMacSystemFont,=
'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif,'Apple Color Emoji',=
'Segoe UI Emoji','Segoe UI Symbol'; mso-line-height-alt: 16.8px; color: #00=
0; line-height: 1.2;"> <p style=3D"box-sizing: border-box; line-height: inh=
erit; margin: 0; font-size: 14px; mso-line-height-alt: 16.8px;"> <span styl=
e=3D"box-sizing: border-box; word-break: break-word; font-size: 14px;">File=
 type</span> </p> </div> </div> </td> </tr> </table> <table border=3D"0" ce=
llpadding=3D"0" cellspacing=3D"0" class=3D"text_block block-2" role=3D"pres=
entation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-r=
space: 0; word-break: break-word;" width=3D"100%"> <tr style=3D"box-sizing:=
 border-box;"> <td class=3D"pad" style=3D"box-sizing: border-box;"> <div st=
yle=3D"box-sizing: border-box; font-family: Arial,sans-serif;"> <div class=
=3D"" style=3D"box-sizing: border-box; font-size: 14px; font-family: 'Atlas=
 Grotesk',-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helv=
etica,Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbo=
l'; mso-line-height-alt: 16.8px; color: #000; line-height: 1.2;"> <p style=
=3D"box-sizing: border-box; line-height: inherit; margin: 0; font-size: 14p=
x; mso-line-height-alt: 16.8px;"> <span style=3D"box-sizing: border-box; wo=
rd-break: break-word; font-size: 16px;"> <strong style=3D"box-sizing: borde=
r-box;">JPG</strong> </span> </p> </div> </div> </td> </tr> </table> </td> =
<td align=3D"left" class=3D"column column-3" style=3D"box-sizing: border-bo=
x; mso-table-lspace: 0; mso-table-rspace: 0; font-weight: 400; text-align: =
left; vertical-align: middle; width: 14%; padding-top: 0!important; padding=
-bottom: 0!important;" valign=3D"middle" width=3D"14%"> <table border=3D"0"=
 cellpadding=3D"0" cellspacing=3D"0" class=3D"image_block block-1" role=3D"=
presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-tab=
le-rspace: 0;" width=3D"100%"> <tr style=3D"box-sizing: border-box;"> <td a=
lign=3D"right" class=3D"pad" style=3D"box-sizing: border-box; width: 100%; =
padding-right: 12px;" width=3D"100%"> <div style=3D"box-sizing: border-box;=
 width: 32px; height: 32px; max-width: 32px; background-color: #f7f5f2; bor=
der-radius: 8px; overflow: hidden;"><img height=3D"32" src=3D"https://libra=
ry.iterable.com/2477/12274/60a803d59eb84638abfbc52b2e366e04-can-view-access=
.png" style=3D"box-sizing: border-box; display: block; height: 32px; border=
: 0; width: 32px;" title=3D"View Icon" width=3D"32"/></div> </td> </tr> </t=
able> </td> <td align=3D"left" class=3D"column column-4" style=3D"box-sizin=
g: border-box; mso-table-lspace: 0; mso-table-rspace: 0; font-weight: 400; =
text-align: left; border-right: 1px solid #d0d0d3; padding-right: 12px; ver=
tical-align: middle; width: 19.333333333333332%; padding-top: 0!important; =
padding-bottom: 0!important;" valign=3D"middle" width=3D"19.333333333333332=
%"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"text_b=
lock block-1" role=3D"presentation" style=3D"box-sizing: border-box; mso-ta=
ble-lspace: 0; mso-table-rspace: 0; word-break: break-word;" width=3D"100%"=
> <tr style=3D"box-sizing: border-box;"> <td class=3D"pad" style=3D"box-siz=
ing: border-box; padding-top: 3px!important;"> <div style=3D"box-sizing: bo=
rder-box; font-family: Arial,sans-serif;"> <div class=3D"" style=3D"box-siz=
ing: border-box; font-size: 14px; font-family: 'Atlas Grotesk',-apple-syste=
m,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif=
,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol'; mso-line-height-al=
t: 16.8px; color: #000; line-height: 1.2;"> <p style=3D"box-sizing: border-=
box; line-height: inherit; margin: 0; font-size: 14px; mso-line-height-alt:=
 16.8px;"> <span style=3D"box-sizing: border-box; word-break: break-word; f=
ont-size: 14px;">Access</span> </p> </div> </div> </td> </tr> </table> <tab=
le border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"text_block blo=
ck-2" role=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspa=
ce: 0; mso-table-rspace: 0; word-break: break-word;" width=3D"100%"> <tr st=
yle=3D"box-sizing: border-box;"> <td class=3D"pad" style=3D"box-sizing: bor=
der-box;"> <div style=3D"box-sizing: border-box; font-family: Arial,sans-se=
rif;"> <div class=3D"" style=3D"box-sizing: border-box; font-size: 14px; fo=
nt-family: 'Atlas Grotesk',-apple-system,BlinkMacSystemFont,'Segoe UI','Hel=
vetica Neue',Helvetica,Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji=
','Segoe UI Symbol'; mso-line-height-alt: 16.8px; color: #000; line-height:=
 1.2;"> <p style=3D"box-sizing: border-box; line-height: inherit; margin: 0=
; font-size: 14px; mso-line-height-alt: 16.8px;"> <span style=3D"box-sizing=
: border-box; word-break: break-word; font-size: 16px;"> <strong style=3D"b=
ox-sizing: border-box;">Can view=C2=A0</strong> </span> </p> </div> </div> =
</td> </tr> </table> </td> <td align=3D"left" class=3D"column column-5" sty=
le=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; fon=
t-weight: 400; text-align: left; vertical-align: middle; width: 14%; paddin=
g-top: 0!important; padding-bottom: 0!important;" valign=3D"middle" width=
=3D"14%"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"=
image_block block-1" role=3D"presentation" style=3D"box-sizing: border-box;=
 mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tr style=3D"bo=
x-sizing: border-box;"> <td align=3D"right" class=3D"pad" style=3D"box-sizi=
ng: border-box; width: 100%; padding-right: 12px;" width=3D"100%"> <div sty=
le=3D"box-sizing: border-box; width: 32px; height: 32px; max-width: 32px; b=
ackground-color: #f7f5f2; border-radius: 8px; overflow: hidden;"> <img heig=
ht=3D"32" src=3D"https://library.iterable.com/2477/12274/3d6cd60081494b31a3=
5ddc695878cdb0-storage-icon.png" style=3D"box-sizing: border-box; display: =
block; height: 32px; border: 0; width: 32px;" title=3D"Size Icon" width=3D"=
32"/> </div> </td> </tr> </table> </td> <td align=3D"left" class=3D"column =
column-6" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-r=
space: 0; font-weight: 400; text-align: left; border-right: 1px solid #d0d0=
d3; padding-right: 12px; vertical-align: middle; width: 19.333333333333332%=
; padding-top: 0!important; padding-bottom: 0!important;" valign=3D"middle"=
 width=3D"19.333333333333332%"> <table border=3D"0" cellpadding=3D"0" cells=
pacing=3D"0" class=3D"text_block block-1" role=3D"presentation" style=3D"bo=
x-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; word-break:=
 break-word;" width=3D"100%"> <tr style=3D"box-sizing: border-box;"> <td cl=
ass=3D"pad" style=3D"box-sizing: border-box; padding-top: 3px!important;"> =
<div style=3D"box-sizing: border-box; font-family: Arial,sans-serif;"> <div=
 class=3D"" style=3D"box-sizing: border-box; font-size: 14px; font-family: =
'Atlas Grotesk',-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue=
',Helvetica,Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI=
 Symbol'; mso-line-height-alt: 16.8px; color: #000; line-height: 1.2;"> <p =
style=3D"box-sizing: border-box; line-height: inherit; margin: 0; font-size=
: 14px; mso-line-height-alt: 16.8px;"> <span style=3D"box-sizing: border-bo=
x; word-break: break-word; font-size: 14px;">Size</span> </p> </div> </div>=
 </td> </tr> </table> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"=
0" class=3D"text_block block-2" role=3D"presentation" style=3D"box-sizing: =
border-box; mso-table-lspace: 0; mso-table-rspace: 0; word-break: break-wor=
d;" width=3D"100%"> <tr style=3D"box-sizing: border-box;"> <td class=3D"pad=
" style=3D"box-sizing: border-box;"> <div style=3D"box-sizing: border-box; =
font-family: Arial,sans-serif;"> <div class=3D"" style=3D"box-sizing: borde=
r-box; font-size: 14px; font-family: 'Atlas Grotesk',-apple-system,BlinkMac=
SystemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif,'Apple Co=
lor Emoji','Segoe UI Emoji','Segoe UI Symbol'; mso-line-height-alt: 16.8px;=
 color: #000; line-height: 1.2;"> <p style=3D"box-sizing: border-box; line-=
height: inherit; margin: 0; font-size: 14px; mso-line-height-alt: 16.8px;">=
 <span style=3D"box-sizing: border-box; word-break: break-word; font-size: =
16px;"> <strong style=3D"box-sizing: border-box;">455 KB</strong> </span> <=
/p> </div> </div> </td> </tr> </table> </td> </tr> </tbody> </table> </td> =
</tr> </tbody> </table> <table align=3D"center" border=3D"0" cellpadding=3D=
"0" cellspacing=3D"0" class=3D"row row-16 mobile_hide" role=3D"presentation=
" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0=
;" width=3D"100%"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"b=
ox-sizing: border-box;"> <td style=3D"box-sizing: border-box;"> <table alig=
n=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row-=
content stack" role=3D"presentation" style=3D"box-sizing: border-box; mso-t=
able-lspace: 0; mso-table-rspace: 0; border-radius: 0; color: #000; width: =
500px; margin: 0 auto;" width=3D"500"> <tbody style=3D"box-sizing: border-b=
ox;"> <tr style=3D"box-sizing: border-box;"> <td align=3D"left" class=3D"co=
lumn column-1" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-ta=
ble-rspace: 0; font-weight: 400; text-align: left; border-left: 1px solid #=
d0d0d3; border-right: 1px solid #d0d0d3; padding-bottom: 5px; padding-top: =
5px; vertical-align: top; width: 100%;" valign=3D"top" width=3D"100%"> <div=
 class=3D"spacer_block block-1" style=3D"box-sizing: border-box; height: 18=
px; line-height: 18px; font-size: 1px;">=E2=80=8A </div> </td> </tr> </tbod=
y> </table> </td> </tr> </tbody> </table> <!--[if !mso]><!--> <table align=
=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row r=
ow-17 desktop_hide" role=3D"presentation" style=3D"box-sizing: border-box; =
mso-table-lspace: 0; mso-table-rspace: 0; mso-hide: all; display: none; max=
-height: 0; overflow: hidden;" width=3D"100%"> <tbody style=3D"box-sizing: =
border-box;"> <tr style=3D"box-sizing: border-box;"> <td style=3D"box-sizin=
g: border-box;"> <table align=3D"center" border=3D"0" cellpadding=3D"0" cel=
lspacing=3D"0" class=3D"row-content" role=3D"presentation" style=3D"box-siz=
ing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; mso-hide: all; d=
isplay: none; max-height: 0; overflow: hidden; border-radius: 0; color: #00=
0; width: 500px; margin: 0 auto;" width=3D"500"> <tbody style=3D"box-sizing=
: border-box;"> <tr style=3D"box-sizing: border-box;"> <td style=3D"box-siz=
ing: border-box; border-left: 1px solid #d0d0d3; border-right: 1px solid #d=
0d0d3; padding: 5px 0 10px; vertical-align: top;" valign=3D"top"> <table bo=
rder=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"mobile_metadata_tab=
le" role=3D"presentation" style=3D"box-sizing: border-box; mso-hide: all; d=
isplay: none; max-height: 0; overflow: hidden; mso-table-lspace: 0; mso-tab=
le-rspace: 0;" width=3D"100%"> <tbody style=3D"box-sizing: border-box;"> <t=
r style=3D"box-sizing: border-box;"> <td class=3D"mobile_metadata_item" sty=
le=3D"box-sizing: border-box; width: 50%; vertical-align: middle; padding: =
12px 5px 12px 20px;" valign=3D"middle" width=3D"50%"> <table border=3D"0" c=
ellpadding=3D"0" cellspacing=3D"0" role=3D"presentation" style=3D"box-sizin=
g: border-box; mso-hide: all; display: none; max-height: 0; overflow: hidde=
n; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tbody style=
=3D"box-sizing: border-box;"><tr style=3D"box-sizing: border-box;"> <td ali=
gn=3D"center" style=3D"box-sizing: border-box; width: 56px; vertical-align:=
 middle;" valign=3D"middle" width=3D"56"> <div style=3D"box-sizing: border-=
box; width: 48px; height: 48px; max-width: 48px; margin: 0 auto; background=
-color: #f7f5f2; border-radius: 9px; overflow: hidden;"><img height=3D"48" =
src=3D"https://library.iterable.com/2477/12274/8ae472be2fdd4d2eb13fb1a27895=
b021-file-icon.png" style=3D"box-sizing: border-box; display: block; height=
: 48px; border: 0; width: 48px;" title=3D"File Icon" width=3D"48"/></div> <=
/td> <td style=3D"box-sizing: border-box; vertical-align: middle; padding-l=
eft: 8px;" valign=3D"middle"> <div style=3D"box-sizing: border-box; font-fa=
mily: 'Atlas Grotesk',-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetic=
a Neue',Helvetica,Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Se=
goe UI Symbol'; font-size: 14px; line-height: 1.2; color: #000;">File type<=
/div> <div style=3D"box-sizing: border-box; font-family: 'Atlas Grotesk',-a=
pple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,=
sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol'; font-siz=
e: 16px; line-height: 1.2; color: #000; padding-top: 3px;"><strong style=3D=
"box-sizing: border-box;">JPG</strong></div> </td> </tr></tbody> </table> <=
/td> <td class=3D"mobile_metadata_item" style=3D"box-sizing: border-box; wi=
dth: 50%; vertical-align: middle; padding: 12px 20px 12px 5px;" valign=3D"m=
iddle" width=3D"50%"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"=
0" role=3D"presentation" style=3D"box-sizing: border-box; mso-hide: all; di=
splay: none; max-height: 0; overflow: hidden; mso-table-lspace: 0; mso-tabl=
e-rspace: 0;" width=3D"100%"> <tbody style=3D"box-sizing: border-box;"><tr =
style=3D"box-sizing: border-box;"> <td align=3D"center" style=3D"box-sizing=
: border-box; width: 56px; vertical-align: middle;" valign=3D"middle" width=
=3D"56"> <div style=3D"box-sizing: border-box; width: 48px; height: 48px; m=
ax-width: 48px; margin: 0 auto; background-color: #f7f5f2; border-radius: 9=
px; overflow: hidden;"><img height=3D"48" src=3D"https://library.iterable.c=
om/2477/12274/60a803d59eb84638abfbc52b2e366e04-can-view-access.png" style=
=3D"box-sizing: border-box; display: block; height: 48px; border: 0; width:=
 48px;" title=3D"View Icon" width=3D"48"/></div> </td> <td style=3D"box-siz=
ing: border-box; vertical-align: middle; padding-left: 8px;" valign=3D"midd=
le"> <div style=3D"box-sizing: border-box; font-family: 'Atlas Grotesk',-ap=
ple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,s=
ans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol'; font-size=
: 14px; line-height: 1.2; color: #000;">Access</div> <div style=3D"box-sizi=
ng: border-box; font-family: 'Atlas Grotesk',-apple-system,BlinkMacSystemFo=
nt,'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif,'Apple Color Emoj=
i','Segoe UI Emoji','Segoe UI Symbol'; font-size: 16px; line-height: 1.2; c=
olor: #000; padding-top: 3px;"><strong style=3D"box-sizing: border-box;">Ca=
n view</strong></div> </td> </tr></tbody> </table> </td> </tr> <tr style=3D=
"box-sizing: border-box;"> <td class=3D"mobile_metadata_item" style=3D"box-=
sizing: border-box; width: 50%; vertical-align: middle; padding: 12px 5px 1=
2px 20px;" valign=3D"middle" width=3D"50%"> <table border=3D"0" cellpadding=
=3D"0" cellspacing=3D"0" role=3D"presentation" style=3D"box-sizing: border-=
box; mso-hide: all; display: none; max-height: 0; overflow: hidden; mso-tab=
le-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tbody style=3D"box-siz=
ing: border-box;"><tr style=3D"box-sizing: border-box;"> <td align=3D"cente=
r" style=3D"box-sizing: border-box; width: 56px; vertical-align: middle;" v=
align=3D"middle" width=3D"56"> <div style=3D"box-sizing: border-box; width:=
 48px; height: 48px; max-width: 48px; margin: 0 auto; background-color: #f7=
f5f2; border-radius: 9px; overflow: hidden;"><img height=3D"48" src=3D"http=
s://library.iterable.com/2477/12274/3d6cd60081494b31a35ddc695878cdb0-storag=
e-icon.png" style=3D"box-sizing: border-box; display: block; height: 48px; =
border: 0; width: 48px;" title=3D"Size Icon" width=3D"48"/></div> </td> <td=
 style=3D"box-sizing: border-box; vertical-align: middle; padding-left: 8px=
;" valign=3D"middle"> <div style=3D"box-sizing: border-box; font-family: 'A=
tlas Grotesk',-apple-system,BlinkMacSystemFont,'Segoe UI','Helvetica Neue',=
Helvetica,Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI S=
ymbol'; font-size: 14px; line-height: 1.2; color: #000;">Size</div> <div st=
yle=3D"box-sizing: border-box; font-family: 'Atlas Grotesk',-apple-system,B=
linkMacSystemFont,'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif,'A=
pple Color Emoji','Segoe UI Emoji','Segoe UI Symbol'; font-size: 16px; line=
-height: 1.2; color: #000; padding-top: 3px;"><strong style=3D"box-sizing: =
border-box;">455 KB</strong></div> </td> </tr></tbody> </table> </td> <td s=
tyle=3D"box-sizing: border-box; width: 50%;" width=3D"50%">=C2=A0</td> </tr=
> </tbody> </table> </td> </tr> </tbody> </table> </td> </tr> </tbody> </ta=
ble> <!--<![endif]--> <table align=3D"center" border=3D"0" cellpadding=3D"0=
" cellspacing=3D"0" class=3D"row row-18 desktop_hide" role=3D"presentation"=
 style=3D"box-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0;=
 mso-hide: all; display: none; max-height: 0; overflow: hidden;" width=3D"1=
00%"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: bo=
rder-box;"> <td style=3D"box-sizing: border-box;"> <table align=3D"center" =
border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row-content stack=
" role=3D"presentation" style=3D"box-sizing: border-box; mso-hide: all; dis=
play: none; max-height: 0; overflow: hidden; mso-table-lspace: 0; mso-table=
-rspace: 0; border-radius: 0; color: #000; width: 500px; margin: 0 auto;" w=
idth=3D"500"> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-si=
zing: border-box;"> <td align=3D"left" class=3D"column column-1" style=3D"b=
ox-sizing: border-box; mso-table-lspace: 0; mso-table-rspace: 0; font-weigh=
t: 400; text-align: left; border-left: 1px solid #d0d0d3; border-right: 1px=
 solid #d0d0d3; padding-bottom: 5px; padding-top: 5px; vertical-align: top;=
 width: 100%;" valign=3D"top" width=3D"100%"> <div class=3D"spacer_block bl=
ock-1" style=3D"box-sizing: border-box; height: 18px; line-height: 18px; fo=
nt-size: 1px;">=E2=80=8A</div> </td> </tr> </tbody> </table> </td> </tr> </=
tbody> </table> <table align=3D"center" border=3D"0" cellpadding=3D"0" cell=
spacing=3D"0" class=3D"row row-20" role=3D"presentation" style=3D"box-sizin=
g: border-box; mso-table-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <=
tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: border-bo=
x;"> <td style=3D"box-sizing: border-box;"> <table align=3D"center" border=
=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"row-content stack" role=
=3D"presentation" style=3D"box-sizing: border-box; mso-table-lspace: 0; mso=
-table-rspace: 0; color: #000; width: 500px; margin: 0 auto;" width=3D"500"=
> <tbody style=3D"box-sizing: border-box;"> <tr style=3D"box-sizing: border=
-box;"> <td align=3D"left" class=3D"column column-1" style=3D"box-sizing: b=
order-box; mso-table-lspace: 0; mso-table-rspace: 0; font-weight: 400; text=
-align: left; vertical-align: top; width: 100%;" valign=3D"top" width=3D"10=
0%"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" class=3D"html_=
block block-1" role=3D"presentation" style=3D"box-sizing: border-box; mso-t=
able-lspace: 0; mso-table-rspace: 0;" width=3D"100%"> <tr style=3D"box-sizi=
ng: border-box;"> <td class=3D"pad" style=3D"box-sizing: border-box;"> <div=
 align=3D"center" class=3D"ib-email-footer" style=3D"box-sizing: border-box=
; font-family: Arial,'Helvetica Neue',Helvetica,sans-serif; text-align: cen=
ter; background-color: #F1F2F4!important;"><table align=3D"center" bgcolor=
=3D"#F1F2F4" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" width=3D"100%=
"> <tbody> <tr> <td align=3D"center" style=3D"padding:24px 0;"> <table alig=
n=3D"center" border=3D"0" cellpadding=3D"0" cellspacing=3D"0" width=3D"92%"=
> <tbody> <tr> <td align=3D"center"> <table align=3D"left" border=3D"0" cel=
lpadding=3D"0" cellspacing=3D"0" role=3D"presentation"> <tr> <td align=3D"c=
enter"> <a href=3D"https://links.dropbox.com/u/click?_t=3D60154b197d654466a=
40480a2b908d3b7&amp;_m=3D75252f41b57f47e588f52d03202efe0b&amp;_e=3DhH3WD5o0=
NxcWyIebdX1AE83jTd5WXTvTW1XV01bXsTlCPenpa3LRVBf0GyiwpiSPSc6bxemIKU24O6mjd3M=
4m9cvzk3SlZvkCcnN_DO71nz1a9nGlax4DiCe4zhk1-sgBTSovRRbRjC4gBBmmw5sqIrfoT2duH=
_x40iAjb2zGPXGgKnmtuBV_MRot7mfnG2pUvDL0cB0pvo3Ma394GCHmMxAM6YFVFHkInhXFCau3=
QIEQFWVVzHuX4nEZIuZhEW90LFZN3NL3jlkxyNIkGYkPXOnuGEdJNe8z0J0TYEHGM9p0NH7FNor=
0LTsbArQ6wwoNZ_mMXVFuHJdMxe-TN_SKwbBJ81Copfi98Fq0h5WhjFXHqF-NYiCMaOJLCx3ExY=
oJ5bhxAs--_-Tph_kEbWPj5qre7qchsbncbIKkcwwxAVBFkAaH5zPn-raUDyDq_eg&amp;dbx_c=
ampid=3D19504419&amp;dbx_src=3Demail&amp;dbx_track=3DAAM2nbgyjrRwhkRY54d1SH=
PwtE9XJ0ystvuT8K5Owf-mtdKLa9BOvk45boTOTTJODCFz5f_SO-EBhbO4lYhylHPpzYxjzoYr1=
X82RtiumPuNFg" target=3D"_blank"> <img src=3D"https://library.iterable.com/=
2477/12274/c4a9fd9a364f43f8ae3cdaa56dfa2c6c-GreyTwitter.png" style=3D"displ=
ay:inline-block; border:0;" width=3D"30"/> </a> </td> <!-- spacer --> <td w=
idth=3D"26">=C2=A0</td> <td align=3D"center"> <a href=3D"https://links.drop=
box.com/u/click?_t=3D60154b197d654466a40480a2b908d3b7&amp;_m=3D75252f41b57f=
47e588f52d03202efe0b&amp;_e=3DhH3WD5o0NxcWyIebdX1AE6MoMoSkLqDnsJ2nMlRQjkDof=
NFGJ9JOMKV6uXIGBOL44adfPCKcDJIMKUoec6rDx1y_nHFeBzIBtdlk-VXWAd0izfJBf5grd0eF=
nYpl2M7EX0IlB3rpuWPWLBmL1hu-G9lljEdJCQLNTbR5ajxmU15sHL14_5Zpz4SgGJf0RZID_Wp=
rZQA_UVrH9CbRLwHIgiLF4AoCfEY23rCqaH0CZqPNfFVozhUomMDbIbxo0sVdTStcozuIRpfoa3=
DQehU8nZ_-dGa8cxZeOEdBL03NdMsIua1Q8m5iT6NyJtIYAHbIoQNLcryxE6XpCtduLMZq6Lnaa=
ZTaoxdKSLNyvaSCPg959JIBJ3t-2PKM--YLDVvAGJM1mBK1LaZ_YqhDtVh1RCL06fJHQooe506f=
7TlLdqru55w0LXDG4o7RUlLaKJmz&amp;dbx_campid=3D19504419&amp;dbx_src=3Demail&=
amp;dbx_track=3DAAM2nbgyjrRwhkRY54d1SHPwtE9XJ0ystvuT8K5Owf-mtdKLa9BOvk45boT=
OTTJODCFz5f_SO-EBhbO4lYhylHPpzYxjzoYr1X82RtiumPuNFg" target=3D"_blank"> <im=
g src=3D"https://library.iterable.com/2477/12274/1e6262ea7179463188c2b64aae=
eb6b7b-GreyFacebook.png" style=3D"display:inline-block; border:0;" width=3D=
"30"/> </a> </td> <!-- spacer --> <td width=3D"26">=C2=A0</td> <td align=3D=
"center"> <a href=3D"https://links.dropbox.com/u/click?_t=3D60154b197d65446=
6a40480a2b908d3b7&amp;_m=3D75252f41b57f47e588f52d03202efe0b&amp;_e=3DhH3WD5=
o0NxcWyIebdX1AE1eVdrJKTMveOZial_BlnhWn9phhoELgXkbjpnYoDngIWHT7_bSlbUQKM9xAh=
dV-Rh-tCNuOvba1jrQep4PNBB3h2kkmX4hr7RtseIEpy8oMCvr7wNc93lFYEJr0ddNx9x6axeR2=
Pxbst03prwIuDuQbBY0wVdwlJDA52nJlwYcDbzp8d0i1ZrNHa4tRtpcBkLuBBhZNiXFqtRQ3PVl=
wvMb76ABmjS9pkYwJ49FIReJd55WFViHKkvk_77U5KOyfueOR3FNw0rMxGRZG9wVlmc1Z3iUNw_=
rfnaDGoaRomL48G2bp-uIAcs6v1KkD2MPAK864gZO1a4BNTIlGQj11Lvxnh6sPFtMVeA127qqRc=
EOoejfFiTb3E1dccSYys4ZWB8Xk6-rZPF41doqyJgRKqGMDTOqYruI26vmEpWbIXabT2dUTAy4M=
4BcXtnc0hXsc8Q%3D%3D&amp;dbx_campid=3D19504419&amp;dbx_src=3Demail&amp;dbx_=
track=3DAAM2nbgyjrRwhkRY54d1SHPwtE9XJ0ystvuT8K5Owf-mtdKLa9BOvk45boTOTTJODCF=
z5f_SO-EBhbO4lYhylHPpzYxjzoYr1X82RtiumPuNFg" target=3D"_blank"> <img src=3D=
"https://library.iterable.com/2477/12274/3bcbefa1368042c89433c77d840d8ab0-G=
reyYoutube.png" style=3D"display:inline-block; border:0;" width=3D"30"/> </=
a> </td> </tr> </table> </td> </tr> <tr> <td align=3D"center" style=3D"padd=
ing:20px 0px;"> <table border=3D"0" cellpadding=3D"0" cellspacing=3D"0" wid=
th=3D"100%"> <tbody> <tr> <td align=3D"left" style=3D"padding:0px;font-fami=
ly:'Atlas Grotesk',-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetic=
a Neue', Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji=
', 'Segoe UI Symbol';font-size:10px; line-height: 14px; color:#1A1918;">Thi=
s email was sent to <a href=3D"mailto:matthewshannonamos01@gmail.com" style=
=3D"color:#0061FF;text-decoration: underline;">matthewshannonamos01@gmail.c=
om</a> </td> </tr> <tr> <td align=3D"left" style=3D"padding:0px;font-family=
:'Atlas Grotesk',-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica =
Neue', Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',=
 'Segoe UI Symbol';font-size:10px; line-height: 14px; color:#1A1918;">Dropb=
ox, Inc., PO Box 77767, San Francisco, CA 94107 </td> </tr> <tr> <td align=
=3D"left" style=3D"padding:0px;font-family:'Atlas Grotesk',-apple-system, B=
linkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Helvetica, Arial, sans-ser=
if, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';font-size:10px=
; line-height: 14px; color:#1A1918;"><br/> </td> </tr> <tr> <td align=3D"le=
ft" style=3D"padding:0px;font-family:'Atlas Grotesk',-apple-system, BlinkMa=
cSystemFont, 'Segoe UI', 'Helvetica Neue', Helvetica, Arial, sans-serif, 'A=
pple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';font-size:10px; line=
-height: 14px; color:#1A1918;">Dropbox never asks you to call a number, mov=
e money, or share passwords in a share invite. Is there an issue? <a href=
=3D"https://links.dropbox.com/u/click?_t=3D60154b197d654466a40480a2b908d3b7=
&amp;_m=3D75252f41b57f47e588f52d03202efe0b&amp;_e=3DhH3WD5o0NxcWyIebdX1AE-s=
DN8SKtQJMOdYLhfzqfdf3_0on1ffNxd2nFftSWvv0Oc7XIp1bU44yaa_MR1YwWIwfBQs0VU6wNL=
Xg6RvyEdV_jzqPhlAc2YHNe1_Ogwpu5ZShZ9NMFg05LA-_lhbwsXv7zEGiWjOytyUWCjTbMNqqC=
ulMbJusjZ2uqlugs3yvVu9diBOYhJJtb463SUOSr_YHaFBOQnKYpzKBYuk19kefxUMzW-eTGQ43=
QLCF8b_kvzVZAPMXBxKp1BYY8c8MRUxvF_UYYavFWjGG2hyfhgug1wtGsv-n6GDSRs5t3vER62C=
0u50JKJOdp7ARs1VnzCpE3Rr_Lj7yy4isAtXcIifUinOdohdu8trywuboBp3PvpEXp_8WlJ0FTG=
DspBJnlyMlzmYoHoURu9gX715reZpzGen7sWhAq_R7sad2y05lye4BjFTvnxRmIi8ZZmj4Ik2qi=
gbHQfGuva2JbBcJtqVpWXsEilHRDU9u_QtZp44R3tsNwN_xnijcuy7hV0OCJfs1FS_N0UnYjkTn=
934NBqXK55XULSKfZ2lb0DBVrBeleWqWAEDlu7-Dwi6p81Ol4MK6t7Eb8lX3ZFZXE3-4orir4GP=
Ee05MDdx5vfm5CiRauhklFVMVJniWd4ngLlPDvleWfxh1uq2C-lNDHb66SpM%3D&amp;dbx_cam=
pid=3D19504419&amp;dbx_src=3Demail&amp;dbx_track=3DAAM2nbgyjrRwhkRY54d1SHPw=
tE9XJ0ystvuT8K5Owf-mtdKLa9BOvk45boTOTTJODCFz5f_SO-EBhbO4lYhylHPpzYxjzoYr1X8=
2RtiumPuNFg" style=3D"color:#0061FF;text-decoration: underline;" target=3D"=
_blank">Report to Dropbox </a> </td> </tr> </tbody> </table> </td> </tr> </=
tbody> </table> </td> </tr> </tbody> </table></div> </td> </tr> </table> </=
td> </tr> </tbody> </table> </td> </tr> </tbody> </table> </td> </tr> </tbo=
dy> </table> <!-- End --> </body> </html>
--===============7549808131832588495==--

On Wed, Nov 25, 2026 at 3:17 PM Matthew Shannon Amos <matthewshannonamos01@gmail.com> wrote:
Thanks for the tip! 
Minimal Examples
RSS 2.0
XML

<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0">
  <channel>
    <title>Example Feed</title>
    <link>https://example.org/</link>
    <description>Latest updates and entries.</description>
    <item>
      <title>First Entry</title>
      <link>https://example.org/posts/first-entry</link>
      <guid isPermaLink="true">https://example.org/posts/first-entry</guid>
      <pubDate>Wed, 25 Nov 2026 15:00:00 -0400</pubDate>
      <description><![CDATA[<p>Summary or full content here.</p>]]></description>
    </item>
  </channel>
</rss>
Atom 1.0 (RFC 4287)
XML

<?xml version="1.0" encoding="utf-8"?>
<feed xmlns="http://www.w3.org/2005/Atom">
  <title>Example Feed</title>
  <link href="https://example.org/" />
  <link rel="self" href="https://example.org/atom.xml" />
  <id>https://example.org/feed</id>
  <updated>2026-11-25T15:00:00-04:00</updated>
  <entry>
    <title type="text">First Entry</title>
    <link href="https://example.org/posts/first-entry" />
    <id>urn:uuid:123e4567-e89b-12d3-a456-426614174000</id>
    <updated>2026-11-25T15:00:00-04:00</updated>
    <summary type="html">&lt;p&gt;Summary or full content here.&lt;/p&gt;</summary>
  </entry>
</feed>
When to Use Which
Choose Atom when you want strict validation, standardized ISO 8601 timestamps, clear distinction between plain text and HTML/XHTML, and unambiguous <id> fields—especially useful for structured data pipelines and automated parsers.

Choose RSS 2.0 when maximum backward compatibility with legacy feed readers, podcast directories, and broad web syndication tools is your top priority.

Are you looking to generate Atom/RSS feeds from an existing dataset or script, parse feeds in Python/JS, or embed feed links on a page?


On Wed, Nov 25, 2026 at 3:14 PM Matthew _Shannon_Amos01 <matthew.shannon.amos75@hotmail.com> wrote:
<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0">
  <channel>
    <title>Example Feed</title>
    <link>https://example.org/</link>
    <description>Latest updates and entries.</description>
    <item>
      <title>First Entry</title>
      <link>https://example.org/posts/first-entry</link>
      <guid isPermaLink="true">https://example.org/posts/first-entry</guid>
      <pubDate>Wed, 25 Nov 2026 15:00:00 -0400</pubDate>
      <description><![CDATA[<p>Summary or full content here.</p>]]></description>
    </item>
  </channel>
</rss>

Minimal Examples
RSS 2.0
Atom 1.0 (RFC 4287)
When to Use Which
Choose Atom when you want strict validation, standardized ISO 8601 timestamps, clear distinction between plain text and HTML/XHTML, and unambiguous <id> fields—especially useful for structured data pipelines and automated parsers.
Choose RSS 2.0 when maximum backward compatibility with legacy feed readers, podcast directories, and broad web syndication tools is your top priority.
Are you looking to generate Atom/RSS feeds from an existing dataset or script, parse feeds in Python/JS, or embed feed links on a page?



https://docs.google.com/videos/d/1uKRJjU6I441aTDsrHAxtdyzaG5enFMNVKcZoicAwg0o/edit?scene=id.p#scene=id.p<iframe src="//www.slideshare.net/slideshow/embed_code/key/dDnbggDJuZh1A0" width="668" height="714" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/slideshow/papa-legba-nb-white-boy-expo-2360-plus-pagesgoogle-com/273409254" title="Papa.Legba.NB White-Boy-Expo-2360@plus.pagesgoogle.com" target="_blank">Papa.Legba.NB White-Boy-Expo-2360@plus.pagesgoogle.com</a> </strong> from <strong><a href="//www.slideshare.net/shannonannie506" target="_blank">Matthew Shannon Amos</a></strong> </div>

From: Matthew Shannon Amos Amos (via Dropbox)
Sent: Wednesday, November 25, 2026 9:15 AM
To: matthewshannonamos01@gmail.com
Subject: Re: Matthew Shannon Amos Amos shared "Screenshot_20261125_091316_Tuta.jpg" with you

https://www.dropbox.com/scl/fi/qi7u7pwfd53wez2u017ep/Screenshot_20261125_091316_Tuta.jpg?rlkey=ztn23y7axbdoh4jzay1v03pv5&st=ndbk8fwg&dl=0
Dropbox 
Matthew Shannon Amos Amos (sean.chodum.burns@gmail.com) shared Screenshot_20261125_091316_Tuta.jpg with you

 

https://www.dropbox.com/scl/fi/qi7u7pwfd53wez2u017ep/Screenshot_20261125_091316_Tuta.jpg?rlkey=ztn23y7axbdoh4jzay1v03pv5&st=ndbk8fwg&dl=0
