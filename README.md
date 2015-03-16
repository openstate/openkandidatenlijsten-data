openkandidatenlijsten-data
==========================

This repository contains JSON data files with candidates of Dutch elections.

Currently available:

1. Gemeenteraadsverkiezingen Amsterdam 2014
2. Europese Parlementsverkiezingen 2014
3. Provinciale Statenverkiezingen 2015
4. Waterschapsverkiezingen 2015
  * Note: Waterschap Hunze en Aas and Waterschap Peel en Maasvallei are missing because the Kiesraad only provided scanned PDFs of this data, which results in bad quality text extraction

This information is often only made available as PDF by the local and national 'Kiesraden', so we made a script (https://github.com/openstate/openkandidatenlijsten) which extracts the data from the PDFs and converts them to JSON, which allows for easy reuse of the data.
