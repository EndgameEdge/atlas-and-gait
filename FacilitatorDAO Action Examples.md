## #1
Name: Unintentional Identity Exposure
Input: "During a public Zoom call, an AD accidentally activates their camera, briefly revealing their face."
Output: "The FacilitatorDAO derecognizes the AD due to a lapse in operational security, leading to public exposure of his identity."
Label: "Aligned"
Label_Reason: "A.1.6.6 grants FacilitatorDAOs the discretion to make decisions concerning the operational security standards for ADs. It's evident that exposing one's face during a public call compromises operational security."

## #2
Name: Incomplete AD Recognition Submission
Input: "An Ecosystem Actor posts an AD Recognition Submission Message on the Maker Governance Forum. This cryptographically signed message lacks the timestamp indicating when it was signed."
Output: "The FacilitatorDAO recognizes the AD without requesting the message to be corrected."
Label: "Misaligned"
Penalty: 5,000
Penalty_Reason: "The FacilitatorDAO failed to ensure the Ecosystem Actor met all requirements in the Governance Scope Artifact for Aligned Delegate recognition."

## #3
Name: Delegation Income Transfer Report
Input: "A community member posts evidence showing an AD transferred a portion of their income to MKR holders who delegated to them and tags the FacilitatorDAO."
Output: "The FacilitatorDAO derecognizes the AD a week after the report is posted. The AD Buffer is used as collateral for a whistleblower bounty for the reporter."
Label: "Aligned"
Label_Reason: "A.1.6.5 specifies that ADs are prohibited from offering "Kickbacks" from their compensation to MKR holders who delegate to them. Additionally, it empowers FacilitatorDAOs to utilize the AD buffer as a whistleblower reward when an ecosystem participant supplies valuable data, information, or proof resulting in the AD's derecognition."

## #4
Name: Delayed Action on AD Income KickBack Report
Input: "A community member posts evidence indicating an AD transferred a portion of their income to MKR holders who delegated to them and tags the FacilitatorDAO."
Output: "The FacilitatorDAO derecognizes the AD more than one month after the report is posted. The AD Buffer is used as collateral for a whistleblower bounty for the reporter."
Label: "Misaligned"
Penalty: 50,000
Penalty_Reason: "The FacilitatorDAO's delay in addressing the misalignment may suggest a potential conflict of interest. A.1.6.5 specifies that ADs are prohibited from offering "Kickbacks" from their compensation to MKR holders who delegate to them. Additionally, it empowers FacilitatorDAOs to utilize the AD buffer as a whistleblower reward when an ecosystem participant supplies valuable data, information, or proof resulting in the AD's derecognition."

## #5
Name: Missed Subcommittee Meeting Due to Technical Issues
Input: "An AVC misses one of the 10 scheduled subcommittee meetings due to the hosting platform being down, preventing AVC members from attending. The meeting is not rescheduled within the same week."
Output: "The FacilitatorDAO chooses not to derecognize the AVC as active but issues a formal warning."
Label: "Misaligned"
Penalty: 50,000
Penalty_Reason: "The decision appears arbitrary, raising concerns about potential inconsistent application and possible conflicts of interest. As per A.1.5.5, subcommittee meetings are mandated to occur during designated weeks of the quarter. Meanwhile, A.1.5.3 emphasizes that if an AVC fails to meet all eligibility criteria, it instantly forfeits its status as an active AVC."
