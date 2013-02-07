# vACCBiH sector/pof files for VRC

# Changelog

**Caution! These files are only usable with _VRC_ and are not compatible with Euroscope!**

**For Euroscope use [this](https://github.com/tarakanbg/vaccbih_sct_files) version.**

## v. 1302

### Global changes

* Changed coordinates for waypoints TIMID and NORPI in accordance with AIRAC 1302 and NOTAMs A2668/12 and A0085/13
* Slightly adjusted coordinates for KEB, KIS VORs to match published navdata
* Added waypoints: ADNAN, EMKES. Remember to display them via your clients "View Settings"

### LQSA changes

* All newly published LQSA star diagrams can now be displayed on radar for reference. Tracks are combined where applicable to mimize screen clutter.
  Check your View > Diagrams to enable disable the STAR tracks. Please note that the approach tracks are also depicted
  as STARS, as the sct file format does not separately support approaches.
* Added the new ILS S approach and its transitions as a radar diagram (under the STARS section). Please study the chart carefully,
  as this is perhaps *the most important addition* of this update, contaning the transitions from the new IAF fixes ADNAN, EMKES, NORPI and TIMID where
  the new STARs terminate to the localizer 12.
* List of the new LQSA STARs as implemented in the new sector file: BOSN1N, NORP1L, SARA1L, KEB1P, VRAN1M, GILU1P, GILU1L, MOST1L, MOST1P.
  Easy mnemonics for the new STARs: all "L" STARS terminate at TIMID, all "P" STARs terminate at ADNAN, all "N" STARs terminate at NORPI,
  all "M" STARs terminate at EMKES

## v. 1211

* Adjusted new frequency for Mostar Tower

## v. 1210

Compared to our [Euroscope new versions](https://github.com/tarakanbg/vaccbih_sct_files)
here's what you get and what you don't:

### What you get

* Accurate updated navaids
* Accurate updated ground layouts for LQSA, LQMO, LQBK
* Accurate updated SID / STAR / APP tracks that can be displayed for reference for LQSA, LQMO, LQBK
  (View => Diagrams... Menu)
* Accurate airspace rendition with correct names
* Accurate station information, frequencies and sq ranges for all BiH ATC stations

### What you don't get

* None of the freetext elements that are only supported by Euroscope
* None of the extended position information, sector ownership logic and vis centers, that are only supported by ES
* No automatic airport activation, automatic metar loading, auto assignable rwys and SIDs, only supported by ES
* No separate GEO zones, all GEO can only be shown or hidden at once


## Installation

### Upgrading from version 0904

**Remove the following files:**

* LQSBV1.4.POF
* LQSB_0904.sct

**Replace with the files from this package:**

* LQSB.sct
* LQSB.POF

Now you can open the new LQSB sector file in your VRC and adjust what features you want displayed.


