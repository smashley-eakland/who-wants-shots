National 2009 H1N1 Flu Survey (NHFS) 
Public-Use Data File (PUF)



WARNING - DATA USE RESTRICTIONS - READ CAREFULLY BEFORE USE!

The Public Health Service Act (Section 308(d)) provides that the 
data collected by the National Center for Health Statistics (NCHS), 
Centers for Disease Control and Prevention (CDC), may be used only 
for the purpose of health statistical reporting and analysis.

Any effort to determine the identity of any reported case is 
prohibited by this law.

NCHS does all it can to ensure that the identity of data subjects 
cannot be disclosed.  All direct identifiers, as well as any 
characteristics that might lead to identification, are omitted 
from the data files.  Any intentional identification 
or disclosure of a person or establishment violates the assurances 
of confidentiality given to the providers of the information.

Therefore, users will:

1. Use the data in these data files for statistical reporting and 
   analysis only.

2. Make no use of the identity of any person or establishment 
   discovered inadvertently and advise the Director, NCHS, of 
   any such discovery (1 (800) 232-4636).

3. Not link these data files with individually identifiable data 
   from other NCHS or non-NCHS data files.

By using these data, you signify your agreement to comply with 
the above requirements.



INTRODUCTION

The National 2009 H1N1 Flu Survey (NHFS) was sponsored by the 
National Center for Immunization and Respiratory Diseases 
(NCIRD) and conducted jointly by NCIRD and the National 
Center for Health Statistics (NCHS), Centers for Disease 
Control and Prevention (CDC). The NHFS was a list-assisted 
random-digit-dialing telephone survey of households, designed
to monitor influenza immunization coverage in the 2009-10 season.

The target population for the NHFS was all persons 6 months or
older living in the United States at the time of the 
interview. Data from the NHFS were used to produce timely estimates 
of vaccination coverage rates for both the monovalent pH1N1 and
trivalent seasonal influenza vaccines.

For more information, see:
http://www.cdc.gov/nchs/nis/about_nis.htm#h1n1



CONTENTS OF THE NHFS PUF

The overall package consists of seven computer files, as follows:

---------------------------------------------------------------------------------
NAME.TYPE                File                 Description	
                         Size (KB)           	
---------------------------------------------------------------------------------
NHFSPUF_README.TXT          8       Readme File (this text)

NHFSPUF_DUG.PDF	 	1,069       NHFS PUF Data User's Guide 
                                    (Adobe Acrobat format)

NHFSPUF_CODEBOOK.PDF      620       NHFS PUF Data Documentation,
                                    Codebook, and Frequencies
                                    (Adobe Acrobat format)

NHFSPUF.DAT            17,459       NHFS PUF Dataset (ASCII format)
                                     
NHFSPUF.SAS                32       SAS Input Statements (ASCII format, SAS v 9.2)

NHFSPUF.R                  47       R Input Statements (ASCII format, R v 2.8.1)

NHFSPUF_QUEX.PDF          444       NHFS Questionnaire 
                                    (Adobe Acrobat format)
                
                                     
---------------------------------------------------------------------------------

The NHFS public-use data file is available in ASCII format. 
The actual file is in a compressed format and can be expanded 
using WinZip or other software.  A SAS program (in ASCII format) 
is provided to facilitate reading the ASCII data file and creating 
a SAS dataset.  The SAS program contains, for each variable in the 
ASCII file, the variable name, its starting position and width, 
labels, and formats. AN R program (in ASCII format) 
is also provided to facilitate reading the ASCII data file and creating 
a R dataset.  The R program contains, for each variable in the 
ASCII file, the variable name, its starting position and width, 
labels, and formats. 

The data file NHFSPUF.DAT can be used for processing by 
statistical software packages that accept ASCII-formatted input, 
or it can be transferred to another computer for processing.

For more information about the NHFS PUF, data users should 
consult the NHFS PUF Data User's Guide and the NHFS PUF 
Data Documentation, Codebook, and Frequencies.  Users of these 
data must review that descriptive and explanatory documentation to 
analyze the data correctly.  These documents are available in PDF 
format.

The NHFS PUF Data User's Guide provides detailed information 
about the design of the NHFS sample, the questionnaire, the 
weighting and estimation procedures, and other important 
information needed for analyzing these data.  

The NHFS PUF Data Documentation, Codebook and Frequencies 
contains indexes of the variables (in both section order and
alphabetical order), the variable responses, and either
unweighted frequencies of categorical variables or 
unweighted summary statistics for continuous variables.

The NHFS files are large.  Please use caution and check the 
capacity of your disk drive before downloading them.
     

Documents in PDF format can be viewed with Adobe Acrobat software.
The Adobe Acrobat Reader can be downloaded from the Adobe Acrobat 
website at:

http://www.adobe.com/products/acrobat/readstep2.html     



UNIQUE IDENTIFIERS AND WEIGHTING

The unique household identification number is SEQNUMHH.
The unique person-level identification number is SEQNUMP.  

SEQNUMP consists of 6 digits: the first five digits are 
SEQNUMHH and the sixth digit uniquely 
identifies the person within the household.

The sampling weight is called FLUWT.



GUIDELINES FOR CITATION OF DATA

With the goal of mutual benefit, the National Center for Health
Statistics (NCHS) and the National Center for Immunization and 
Respiratory Diseases (NCIRD) request that recipients of data files 
cooperate in certain actions related to their use.  Any published 
material derived from these data should acknowledge CDC (NCHS and NCIRD) 
as the original data source and use "NHFS" in the title or as a 
keyword in the abstract. The suggested citation to appear at the 
bottom of all tables is as follows:

       Source: CDC, NCRID and NCHS (2012), National 2009 H1N1 Flu
       Survey.

The reference for the NHFS data file is:

       U.S. Department of Health and Human Services (DHHS).  
       National Center for Health Statistics.  The National 2009
       H1N1 Flu Survey.  Hyattsville, MD: Centers for Disease
       Control and Prevention, 2012.


Published material should also include a disclaimer that 
attributes any analyses, interpretations, or conclusions reached 
to the author (recipient of the data file) and not to NCHS, 
which is responsible only for the initial data.  Consumers who 
wish to publish a technical description of the data should 
ensure that the description is consistent with that published 
by NCHS.

Although the data files have been edited carefully, errors may be 
detected.  Please notify NCHS staff (1 (800) 232-4636) of any errors 
in the NHFS data or documentation.

For additional information on the NHFS public-use data file, please 
contact the NCHS Information Dissemination staff:

Information Dissemination Staff, NCHS
3311 Toledo Road
Hyattsville, MD  20782

Phone:       1 (800) 232-4636
Email:       cdcinfo@cdc.gov
Internet:    http://www.cdc.gov/nchs/