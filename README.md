# Android Image-Forensic-Analysis

This report details a comprehensive forensic investigation into an alleged internet
fraud scheme involving a fake investment website designed to lure individuals into
investing in fraudulent cryptocurrency, promising exceptionally high returns on
investment.
The report outlines the methodologies and tools utilized, presents key findings, and
provides recommendations for future preventative measures and legal actions.

**Tools used:** . Autopsy, 7zip, Android forensic image\
**Methodology:** This encompassing evidence collection, examination, analysis, and reporting. An android image was extracted with 7zip extraction software, which was feed into Autopsy for analysis. The forensic investigation adhered to a rigorous, multi-phase methodology to ensure
the integrity, authenticity, and admissibility of all collected digital evidence. This
structured approach, adapted from established digital forensic principles, involved the
following key stages:

 **1.	collection/Acquisition:**
 
  **• Victim Device Acquisition:** Where available and permissible, forensic images of
relevant storage media (e.g., the mobile phone, tablets) used by victims to interact with the fake website or communicate with
the perpetrators were acquired. Strict chain of custody protocols were
maintained throughout this process, and hardware write-blockers were utilized
to ensure that no data on the original media was inadvertently altered during the
imaging process.

**•	Call logs:** various calls and phone numbers of the conspirators were recovered; this gives more insights into their deceitful act.
**•	Message logs:**  these were also retrieved to ascertain and monitor the trend of communication and strategies in carrying out their elicit fraud.\
**•	Open Source Intelligence (OSINT) Gathering:**  Publicly available information
was systematically collected from various online sources, including social media
platforms, online forums, cryptocurrency communities, and news articles related
to the scam. This intelligence helped in understanding the scam's promotion,
identifying potential victims, and uncovering additional digital footprints of the
perpetrators.\
**•	Artifacts:** web histories, web cookies, web search were also collected this helps to know the tress of web visited by this perpetrator, and the type of search conducted.

**2.	Examination:** Following the secure collection of data, the examination phase involved a meticulous and systematic processing of the acquired digital evidence to identify and extract information pertinent to the investigation. This phase was characterized by:

**•	Data Carving and Recovery:** Advanced data carving techniques were employed
to recover deleted files or fragments of files from unallocated space on acquired
disk images. This was crucial for uncovering hidden or intentionally removed
evidence.

**•	Targeted Keyword Searches:** Extensive keyword searches were conducted
across all acquired data. Keywords included the name of the fake website,
specific cryptocurrency names mentioned in the scam, known aliases of
perpetrators, victim names, and terms commonly associated with investment
schemes (e.g., 'ROI', 'guaranteed returns', 'withdrawal').

**•	File System and Metadata Analysis:** A detailed analysis of file system metadata,
including creation, modification, and access timestamps, was performed to
reconstruct the chronological sequence of events. This helped in understanding
when specific files were created, accessed, or altered, providing insights into the
perpetrators' activities.

**3.	Analysis:**

Message Log analysis:
2024-03-17 03:09:45 WAT
Deduced the name of the alleged suspect to be Bro Sam from the message supposedly to be from his pastor.
2024-03-17 03:19:10 WAT
A scam idea was mention to be carried out
2024-03-17 03:20:44 WAT 
A fake investment crypto currency website was to be created to lure in innocent people
2024-03-17 03:23:45 WAT
A bitcoin wallet address to be used 16AtGJbaxL2kmzx4mW5ocpT2ysTWxmacWn. Which actually belong to Woodberry
2024-03-17 04:29:40 WAT
The fake investment website was actually created.




