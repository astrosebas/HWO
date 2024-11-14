# HPIC : The Habitable Worlds Observatory Preliminary Input catalog
#
# delimited by '|'
#missing data and null values are given by the string ’null’
#
## Column names

star_name: unique object name in the HPIC
ra: right ascension at epoch J2000 (decimal)
dec: declination at epoch J2000 (decimal)
ra_J2016: right ascension at epoch J2016 (decimal)
dec_J2016: declination at epoch J2016 (decimal)
tic_id: Tess Input Catalog ID
gaia_dr2_id: Gaia DR2 ID
gaia_dr3_id: Gaia DR3 ID
hip_name: Hipparcos ID
tm_name:  2MASS ID
tyc_name: Tycho ID
wds_designation: Washington Double Star catalog ID
simbad_name: Name in the CDS Simbad database
source_list_fl: Flag for the source of the object (either TESS or Gaia)
sy_pmra:  proper motion in RA (mas/yr)
sy_pmraerr: uncertainty in RA proper motion
sy_pmdec: proper motion in DE (mas/yr)
sy_pmdecerr: uncertainty in DE proper motion
sy_pmsrc: source of proper motion
sy_pm_reflink: proper motion bibcode
sy_ujmag: Johnson U mag
sy_ujmagerr: U mag uncertainty
sy_ujmagsrc: U mag source
sy_ujmag_reflink: U mag bibcode
sy_bmag: Johnson B mag
sy_bmagerr: B mag uncertainty
sy_bmagsrc: B mag source
sy_bmag_reflink: B mag bibcode
sy_vmag: Johnson V mag
sy_vmagerr: V mag uncertainty
sy_vmagsrc: V mag source
sy_vmag_reflink: V mag bibcode
sy_rcmag: Johnson-Cousins R mag
sy_rcmagerr: R mag uncertainty
sy_rcmagsrc: R mag source
sy_rcmag_reflink: R mag bibcode
sy_icmag: Johnson-Cousins I mag
sy_icmagerr: I mag uncertainty
sy_icmagsrc: I mag source
sy_icmag_reflink: I mag bibcode
sy_jmag: 2MASS J mag
sy_jmagerr: J mag uncertainty
sy_jmagsrc: J mag source
sy_jmagsrc: J mag bibcode
sy_hmag: 2MASS H mag
sy_hmagerr: H mag uncertainty
sy_hmagsrc: H mag source
sy_hmag_reflink: H mag bibcode
sy_kmag: 2MASS K_s mag
sy_kmagerr: K_s mag uncertainty
sy_kmagsrc: K_s mag source
sy_kmag_reflink: K_s mag bibcode
sy_tmag: Tess mag (all T mags are from TIC 8.2)
sy_tmagerr: Tess mag uncertainty
sy_gaiamag: Gaia magnitude
sy_gaiamagerr: G mag uncertainty
sy_gaiamagsrc: G mag source
sy_gaiamag_reflink: G mag bibcode
sy_bpmag: Gaia B_P mag (same source as r_Gmag)
sy_bpmagerr: B_P mag uncertainty
sy_rpmag: Gaia R_P mag (same source as r_Gmag)
sy_rpmagerr: R_P mag uncertainty
sy_plx: parallax (mas)
sy_plxerr: parallax uncertainty
sy_plxsrc: parallax source
sy_plx_reflink: parallax bibcode
sy_dist: Distance (pc)
sy_disterr: distance uncertainty
sy_distsrc: distance source
sy_dist_reflink: distance bibcode
ambiguous dist fl: flag for distance measurements that deviate from the value given by Simbad
st_spectype: Spectral type from Simbad
st_spectype_reflink: bibcode for spectral type
dwarf_fl: flag if an object is a dwarf star
st_teff: Stellar effective temperature (K)
st_tefferr: Teff uncertainty
st_teffsrc: Teff source
st_teff_reflink: Teff bibcode
st_logg: stellar log surface gravity (from bulk properties, log cgs units)
st_loggerr: uncertainty in bulk log(g)
st_loggsrc: source of bulk log(g)
st_logg_reflink: bulk log(g) bibcode
st_loggspec: stellar log surface gravity (from spectroscopy, log cgs units)
st_loggspecerr: uncertainty in spec log(g)
st_loggspecsrc: source of spec log(g)
st_loggspec_reflink: spec log(g) bibcode
st_met: stellar metallicity in [Fe/H]
st_meterr: [Fe/H] uncertainty
st_metsrc: [Fe/H] source
st_met_reflink: [Fe/H] bibcode
st_lum: log10 stellar luminosity (Lsun)
st_lumerr: log10 luminosity uncertainty
st_lumsrc: luminosity source
st_lum_reflink: log(L) bibcode
st_rad: stellar radius (Rsun)
st_raderr: radius uncertainty
st_radsrc: radius source
st_rad_reflink: radius bibcode
st_mass: stellar mass (Msun)
st_masserr: mass uncertainty
st_masssrc: mass source
st_mass_reflink: mass bibcode
uncertain_M_flag: flag for if mass measurement may be unreliable (boolean)
st_age: stellar age (Gyr)
st_ageerr: age uncertainty
st_agesrc: age source
st_age_reflink: age bibcode
contaminant_fl: Flag for if there are nearby contaminants (boolean)
brightest_sep: angular separation from brightest Gaia contaminant (")
brightest_Gmag:  G magnitude difference with brightest Gaia contaminant
brightest_id:  Gaia id of brightest contaminant
nearest_sep: angular separation from nearest Gaia contaminant (")
nearest_Gmag: G magnitude difference with nearest Gaia contaminant
nearest_id: Gaia id of nearest contaminant
known_binary_fl: flag if star is a known binary
gaia_binary_fl: flag if object is tagged as binary by gaia dr3
wds_comp: WDS component
wds_sep: WDS angular separation (“)
wds_delta_mag: WDS  V magnitude difference
GCNS_companion: Gaia DR3 id for object’s companion in Gaia Catalog of Nearby Stars
GCNS_sep:  GCNS separation (“)
GCNS_mag_dff: GCNS G magnitude difference
sy_planets_flag: flag for if there are known planets
hostname: name of the exoplanet host star in the NASA Exoplanet Archive (only present for planet hosts)