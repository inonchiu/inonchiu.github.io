
---
layout: page
title: The eFEDS survey: The chains of cosmological parameters and the cluster masses
mathjax: true
---

In [Chiu, Klein, et al. submitted][chiu22], we constrained cosmology using a sample of _eROSITA_ clusters selected in the eROSITA Final Equatorial-Depth Survey (eFEDS).

The mass estimates and the chains of the cosmological parameters are released via [this link][releases]. The mass table reads

| Column 	| Context |
| :------ |:--- |
| Name | The cluster name     |
| Z\_BEST\_COMB    | The cluster redshift |
| r500c\_lcdm(wcdm)        | The cluster radius $R_{500\mathrm{c}}$ in arcmin |
| ensemble\_500c\_lcdm(wcdm)        | The ensemble mass $\log\left(\frac{ M_{500\mathrm{c,ens}} }{M_{\odot}/h}\right)$. This is an estimate randomly sampled from the mass posterior $P\left(\log\left(\frac{ M_{500\mathrm{c}} }{M_{\odot}/h} \right)\right)$ |
| median\_500c\_lcdm(wcdm)    | The median of the mass posterior $P\left(\log\left(\frac{ M_{500\mathrm{c}} }{M_{\odot}/h} \right)\right)$ |
| m500c\_lcdm(wcdm)\_hierr, m500c\_lcdm(wcdm)\_loerr    | The 1$\sigma$ upper and lower errors of the mass posterior in $M_{\odot}/h$ |

Note that lcdm (wcdm) denotes the values estimated in a flat $\Lambda$CDM ($w$CDM) cosmology.

If you have used this catalog in your research, please kindly cite [Chiu, Klein, et al. submitted][chiu22].

[chiu22]:https://github.com/inonchiu/eFEDSproducts
[releases]:https://github.com/inonchiu/eFEDSproducts