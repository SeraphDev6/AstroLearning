Description of columns in ep_database_table.csv. Units in ()

id: ASAS-SN ID used to match with light curve
asassn_name: ASAS-SN V-band catalog designation
source: Gaia DR3 Source indentifier
TIC: TESS Input Catalog v8.2 identifier
RA_ICRS: right ascension (deg)
DE_ICRS: declination (deg)
period: orbital period (days)
p2: second orbital/pulsational/rotational period (days)
p2_method_i: method of subtraction method used in section 3.2
group: type of extra-physics variability (pulsation, reflection, etc.)
has_tess: QLP or SPOC light curve available
tess_sectors: Number of TESS sectors with QLP or SPOC light curves
Gmag: Gaia apparent G-band magnitude
absolute_g: Absolute gaia G-band magnitude
bp_rp: Gaia BP-RP color
bp_rp_corrected: Gaia BP-RP color corrected for extinction
parallax_over_error: Gaia parallax / parallax error
rpgeo: Bailer-Jones photogeometric distance (pc)
mwdust_av: V-band extinction from mwdust (mag)
mwdust_ag: G-band extinction (mag)
mwdust_abp: BP-band extinction (mag)
mwdust_arp: RP-band extinction (mag)
gaia_filter: parallax_over_error > 10 and mwdust_av < 2
state: evolutionary state based on CMD position
r1: ATLAS REFCAT-2 r1 statistic (arcsec)
xray_source: boolean flag for X-ray detection
xray_observatory: name of X-ray observatory
xray_citation_key: reference fo X-ray source
xray_ads_link: Link to X-ray detection paper
xray_exposure: Exposure of X-ray observation (sec)
xray_luminosity: X-ray luminosity (erg/s)
xray_separation: Source sky separation for X-ray detection (arcseconds)



