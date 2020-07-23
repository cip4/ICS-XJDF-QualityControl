# Quality Control ICS
The MIS to Quality Control Interoperability Conformance Specification (ICS) defines the exchange of quality control data
from MIS or print production system to quality measurement devices, using XJDF.

This ICS is part of a series of ICS documents that define the exchange of quality control data from Customer to Print Provider, CusQC, or MIS to device, MisQC, using XJDF. The ICS documents of the series are designed to enable end-to-end communication of quality targets and results from a conforming measurement device to the Customer at the level of detail that is appropriate for each interface. This encompasses both the definition of quality control requirements for the
Worker as well as the reporting of quality control data by the Worker.

The major difference between the CusQC and MisQC ICS is that CusQC assumes that the data have been summarized for a Customer quality report whereas the MisQC ICS provides an interface for immediate data from quality control measurement devices to an MIS or print production system. This ICS provides information about the details of the XJDF data for quality control. Dynamic modification of quality control requirements by the Manager is out of scope of this ICS.
This ICS requires the use of at least XJDF version 2.1.

This initial version limits the scope to defining print quality inspection and color quality control of printed sheets and
reels. This ICS has no additional normative ICS dependencies.

<br />

## Development Notes
This project builds two release specifications: One for the Customer and one for the MIS.<br/>
In addition a third, 'Both', development version is created by the CI process for use by the Working Group.

The content and style of each version is determined by the FrameMaker book and a FrameMaker document used as a template.<br/>
The book determines which documents are included, the template determines the style and conditional text settings.

### Both
Is the master working copy and contains all documents (including both covers). This should be the only book used for editing.
* Book: ICS-QC-Both.book
* Template: Template_ICS.fm

### Customer
The Customer version. The book contains a subset of documents and should not be used for editing.
* Book: ICS-QC-CUS.book
* Template: Template_ICS_Cus.fm

### MIS
The MIS version. The book contains a subset of documents and should not be used for editing.
* Book: ICS-QC-MIS.book
* Template: Template_ICS_MIS.fm                          
