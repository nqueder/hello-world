# hello-world
# Hi this is Nazek

This branch was created to practice commit changes and pull requests 


| name | value |
|----|:-------:|
|test1 |test a       tests|
|test2 |test b |


|          | Associated With| Candidate Terms| Comment| Description| Interlex ID| Same As| Super Type CDEs| URL| Was Derived From|
|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|
|Acknowledgements| NIDM, BIDS|         |         |OPTIONAL. Text acknowledging contributions of individuals or institutions beyond those listed in Authors or Funding.|http://uri.interlex.org/ilx_0739308|http://purl.org/nidash/nidm#NumberOfChannels|http://purl.org/nidash/nidm#CalculatedParameter|         |http://purl.org/nidash/bids|
AcquisitionDuration| NIDM, BIDS|         |         |RECOMMENDED. Duration (in seconds) of volume acquisition. Corresponds to DICOM Tag 0018,9073 Acquisition Duration. This field is REQUIRED for sequences that are described with the VolumeTiming field and that not have the SliceTiming field set to allowed for accurate calculation of acquisition time. This field is mutually exclusive with RepetitionTime.|http://uri.interlex.org/ilx_0100259|http://purl.org/nidash/dicom#dicom_00189073|         |         |http://purl.org/nidash/bids|
AnatomicalLandmarkCoordinateSystem| NIDM, BIDS|         |         |OPTIONAL. Defines the coordinate system for the anatomical landmarks. See Appendix VIII: preferred names of Coordinate systems. If Other, provide definition of the coordinate system in AnatomicalLandmarkCoordinateSystemDescription.|http://uri.interlex.org/ilx_0739357|http://purl.org/nidash/dicom#dicom_00180021|http://purl.org/nidash/nidm#ImageContrastType|         |http://purl.org/nidash/bids|
AnatomicalLandmarkCoordinateSystemDescription| NIDM, BIDS|         |         |OPTIONAL. Freeform text description or link to document describing the Head Coil coordinate system system in detail.|http://uri.interlex.org/ilx_0739356|http://purl.org/nidash/nidm#NumberOfChannels|http://purl.org/nidash/nidm#ImageContrastType|https://bids-specification.readthedocs.io/en/common-derivatives/05-derivatives/01-introduction.html|http://purl.org/nidash/bids|
AnatomicalLandmarkCoordinateUnits| NIDM, BIDS|         |         |OPTIONAL. Units of the coordinates of AnatomicalLandmarkCoordinateSystem. MUST be m, cm, or mm.|http://uri.interlex.org/ilx_0739355|http://purl.org/nidash/dicom#dicom_00189073|         |         |http://purl.org/nidash/bids|
AnatomicalLandmarkCoordinates| NIDM, BIDS|         |         |OPTIONAL. Key:value pairs of the labels and 3-D digitized locations of anatomical landmarks, interpreted following the AnatomicalLandmarkCoordinateSystem, e.g., {NAS: [12.7,21.3,13.9], LPA: [5.2,11.3,9.6], RPA: [20.2,11.3,9.1]}.|http://uri.interlex.org/ilx_0739358|http://purl.org/nidash/nidm#NumberOfChannels|         |         |http://purl.org/nidash/bids|
AssociatedEmptyRoom| NIDM, BIDS|AssociatedEmptyRoom|This term should be more specific so that it is clear that it refers to a file. Could also use nidm:AcquisitionObject resulting from a nidm:Acquisition activity where the label is Empty Room.|RECOMMENDED. Relative path in BIDS folder structure to empty-room file associated with the subject's MEG recording. The path needs to use forward slashes instead of backward slashes (e.g. sub-emptyroom/ses-/meg/sub-emptyroom/ses-task-noise/run-meg.ds).|http://uri.interlex.org/ilx_0739354|http://purl.org/nidash/nidm#Magnetoencephalography|http://purl.org/nidash/nidm#ImageContrastType|https://bids-specification.readthedocs.io/en/common-derivatives/05-derivatives/01-introduction.html|http://purl.org/nidash/bids|
CBV| NIDM, BIDS|         |         |cbv|http://uri.interlex.org/ilx_0739349|http://purl.org/nidash/nidm#CerebralBloodVolume|http://purl.org/nidash/nidm#CalculatedParameter|         |http://purl.org/nidash/bids|
DigitizedLandmarks| NIDM, BIDS|         |         |REQUIRED. Boolean (true or false) value indicating whether anatomical landmark points (i.e. fiducials) are contained within this recording.|http://uri.interlex.org/ilx_0739330|http://purl.org/nidash/nidm#NumberOfChannels|http://purl.org/nidash/nidm#AcquisitionMethod|         |http://purl.org/nidash/bids|
