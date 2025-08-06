📌 1. What is the Computer Forensics Investigation Process?

Definition:
The Computer Forensics Investigation Process is a systematic procedure used to identify, collect, preserve, analyze, and present digital evidence in a way that is legally admissible in court.
The process ensures that evidence is handled properly, without altering or destroying it, while maintaining a chain of custody.

📌 2. Objectives

       i) Identify the source and cause of a security incident or crime.
       ii) Preserve the integrity of evidence.
       iii) Analyze evidence to reconstruct events.
       iv) Present findings in a clear, legal manner.

📌 3. Key Principles -->

       i) Admissibility – Evidence must meet legal standards to be accepted in court.
       ii) Authenticity – Proof that evidence has not been altered.
       iii) Reliability – Evidence should come from a credible process.
         iv) Integrity – Ensure no tampering during the investigation.
          v) Chain of Custody – Document every action taken on evidence.

📌 4. Computer Forensics Investigation Process – 7 Main Phases

       1. Identification
          i) Recognize an incident or a need for investigation.
         ii) Identify potential sources of evidence:
            a) Computers
            b) Mobile devices
            c) Cloud accounts
            d) Logs
            e) Network devices  
         iii) Example tools: Nmap (scanning), Splunk (log analysis).
       2. Preservation
          i) Protect evidence from alteration or damage.
         ii) Disconnect system from the network (if necessary).
        iii) Create bit-by-bit forensic copies (e.g., with FTK Imager or dd command).
         iv) Generate cryptographic hash (MD5/SHA256) for verification.
          v) Store original media securely.
       3. Collection
          i) Gather evidence from multiple sources:
             a) Hard drives
             b) USB drives
             c) RAM (volatile data)
             d) Network traffic
             e) Cloud backups
         ii) Tools:
             a) FTK Imager
             b) Belkasoft Evidence Center
             c) LiME (Linux Memory Extractor)
             d) Wireshark (network data)

4. Examination -->

   i) Process large volumes of data to find relevant artifacts.
   ii) Recover deleted files.
   iii) Extract metadata (file creation/modification times).
    iv) Convert proprietary formats to standard formats.
    v)  Example tasks:
        a) File carving (using Autopsy, Scalpel)
        b) Registry analysis (using Registry Explorer)
        c) Log review

6. Analysis -->
   
   i) Reconstruct events:
      a) Who did it? (Attribution)
      b) What happened? (Incident type)
      c) When did it happen? (Timeline analysis)
      d) How did it happen? (Attack vector)

   ii) Tools:
       a) Volatility (memory analysis)
       b) Autopsy (disk analysis)
       c) X-Ways Forensics
       d) Plaso/log2timeline (timeline creation)

7. Presentation -->
   
   i) Create a clear, factual report.
   ii) Include:
       a) Summary of findings
       b) Methods used
       c) Evidence screenshots
       d) Timelines
       e) Hash values

  iii) Avoid technical jargon when presenting to non-technical audiences.
   iv) Be ready to testify in court.

8. Decision / Review --> 
   i) Review case outcome.
   ii) Identify improvements for future investigations.
   iii) Close the investigation.
