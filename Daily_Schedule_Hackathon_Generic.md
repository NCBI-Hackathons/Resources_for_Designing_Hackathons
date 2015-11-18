** Daily Schedule for an "Anabolic" Hackathon!**

National Library of Medicine, NIH Campus

If you tweet, please use #NCBIhackathon

Please edit our manuscript!

**Please note that this is a dynamic document, and therefore subject to change at the discretion of the instructors.  **

*Italicized text: Optional Items*

## Example topics (from the August 2015 NCBI-NLM Genomics Hackathon)

**RNAseq**

1.  Homogenous mapping of all human RNAseq reads

2.  Comparison tool for human RNAseq reads

**Variation**

1.  Multiple myeloma clustering team

1a. dbGaP usability script subteam

2.  The variant interpreter super team! (formerly the variant scanning and push button .vcf team).  

+ Github repos have been combined.  Google groups will be (probably today)

2a.  The cell type classification subteam (which will work with homogenous mapping)

**Democratization of Bioinformatics**

1.  The Educational Experience Team

1a.  The Vm library subteam

2.  The SEQR team

Six things for writers

1. (1) Introductory Paragraph

2. (2) Methods Paragraphs

3. (2) Results Paragraphs

4. (1) Discussion Paragraph

#NCBIhackathon

Monday,  XXX -- Location

9:00-9:30: Introductions, Administrative Announcements and **_Building Functional Software_**

    * Discussion of Roles

        * **Lead**

            * Understands the science and assigns roles

        * **Sysadmin**

            * Decides where data and tools go, and implements git for versioning.

            * Deals (in conjunction with technical assistance) with any technical issues (team tech lead)

        * **Writer**

            * Details both product and process for:

                * Documentation 

                * Manuscript

        * Metadata

        * Data Acquisition

        * Data Normalization

        * Downstream Analysis 

            * (Statistics)

        * Documentation 

            * Code and text summaries

    * Discussion of Output

        * Github

            * Live cloning of repos

        * Publishing

            * Journal Strategy Selection

            * Advertising and social media

* 9:30 - 9:45: Technical considerations when using the Amazon cloud for high throughput data analysis, and some more introductions.  

    * Technical note:  Move tools (with git) not data (I know everyone says that, but we mean it this time).

    * Technical note 2: Why we are using GRCh38 for this project.    

* Split into locations for teams (see below)

* 9:45 - 10:00: Role assignments in teams

* 10:00 - 12:15: Sysadmins and Data Acquisition get data, if necessary

    * Everyone else work on first sketch of plan (one page google doc, or similar)

* All teams return to BOR room

* 12:15 - 1:00: Working lunch and sharing of initial searches and discussion between groups (catered lunch opt-in 1; see poll)

* Split into locations for teams (see team spreadsheet -- tab "locations)

* 1:00 - 6:00: Pipeline building <script building>

    * *BLAST and SRA representatives present to help with pipelines*

* *6:00 - 7:30: DINNER (on your own or with group members)*

* *7:30 - 8:30: Implement any remaining code/start pipelines (remote is an option) <script building>*

Tuesday, August 4th -- NLM Board of Regents "BOR" Room

* 9:00 - 9:15: Presentation: Rapid establishment of indels in and out of SRA data structures

* 9:15 - 12:30: Data cleanup, code fixing, and presentation generation

* 12:30 - 1:30 Working lunch (catered lunch opt-in 2; see poll) Each section presents four slides; opportunity for exchange of ideas (*and personnel if necessary*)

* 1:30 - 6:00: Pipeline fixing and implementing suggestions from other group; more data runs

    * *2:30 Coffee break (BOR Room)!*

    * 4:00 - 5:00 Writer’s Group break off 1

* *6:30 - 8:30: GROUP DINNER (see poll); opportunity for feedback on organizational structure and future projects*

Wednesday, August 5th -- NLM Visitor Center

* *8:30 - 9:00:  Breakfast on campus (bring food from to NLM visitor center from 38A cafeteria or elsewhere); more opportunity for feedback on organizational structure and future projects*

* *9:00 - 9:30: Quick tour of SRA BLAST (NLM Visitor Center)*

* 9:30 - 12:00:  Finishing pipelines 

* 12:00 - 1:00: Working lunch (catered lunch opt-in 3; see poll)

* Meeting with Senior NCBI Staff

* 1:00 - 1:10: Potential for transferring data to helix/biowulf

* 1:10 - 5:10: 

    * Writers break off for writers group

    * Editorial representative from NIH library will be there to assist.  

    * Everyone else documents code and writes READMEs

        * Pipeline testing!

            * Bug fixes  

        * Presentation generation

    * Upload code to Github and/or Bitbucket and/or Coders crowd and/or Docker!

* 4:45 - 4:55: Marketing, community interaction, and longevity of code 

    * Who is going to deal with future pull requests?

    * Awards ceremony!

* 4:55 - 5:45: Final Presentations (5 slides per group) 

###

<table>
  <tr>
    <td>Date</td>
    <td>Room</td>
    <td>Teams</td>
    <td>Software Reqs (so far)</td>
  </tr>
  <tr>
    <td>8/3/2015</td>
    <td>Board of Regents "BOR"</td>
    <td>All</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>BOR</td>
    <td>Automatic Scanning, Multiple Myeloma, Pushbutton tool for .vcf</td>
    <td>Repo from RNAseq team from last hackathon (forked into their git site); dbGaP access to 000748 (Ben, Adam and Matt only instance); HISAT; cell line data; updated R; bioconductoR; ClinVar FTP dumps</td>
  </tr>
  <tr>
    <td></td>
    <td>Conference Room "B"</td>
    <td>RNAseq comparison, RNAseq mapping</td>
    <td>HISAT; Callisto; updated R; bioconductoR; samtools</td>
  </tr>
  <tr>
    <td></td>
    <td>"Dungeon" Conference Room</td>
    <td>Educational Resource</td>
    <td>HISAT; Greg Boratyn’s Program; Command Line BLAST (with .vdb SAM output); updated R; bioconductoR</td>
  </tr>
  <tr>
    <td></td>
    <td>B2 library</td>
    <td>SEQR team</td>
    <td>
HISAT; updated R; bioconductoR; JDK 1.8.x Java; maven >= 3.0.3; ant; intellij community edition, recent edition; SOLR 4.10.4; biojava >= 4.1; jython</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>8/4/2015</td>
    <td>Board of Regents "BOR"</td>
    <td>Automatic Scanning, Multiple Myeloma, Pushbutton tool for .vcf</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>"Dungeon" Conference Room</td>
    <td>Educational Resource</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>B2E11 (morning)</td>
    <td>SEQR team</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>B2 library</td>
    <td>SEQR team</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Billings</td>
    <td>RNAseq comparison, RNAseq mapping</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>B1W17A</td>
    <td>Writing room</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>8/5/2015</td>
    <td>NLM Visitor Center</td>
    <td>Automatic Scanning, Multiple Myeloma, Pushbutton tool for .vcf</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>"Dungeon" Conference Room</td>
    <td>Educational Resource</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>B1W17A</td>
    <td>SEQR team</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Billings</td>
    <td>RNAseq comparison, RNAseq mapping</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>38A3S Conference Room</td>
    <td>Writing room</td>
    <td></td>
  </tr>
</table>


Personnel:

<table>
  <tr>
    <td>Building an Educational Environment to Teach Genomic Mapping and Ultrafast BLAST</td>
    <td>Homogenous mapping of 50,101 RNAseq runs to the human genome</td>
    <td>Building a pipeline for automated upload and comparison of RNAseq expression data</td>
    <td>Automatic Scanning of NGS Datasets for Disease Relevant Variants and a Push Button tool for .vcf filtering</td>
    <td>Using SEQR (PSSM BLAST) to Check for Gross (Domain Level) Differences in RNAseq Datasets</td>
    <td>Molecular Matching in Myeloma: Combining RNAseq Data with Drug Response Profiles</td>
    <td>Support Team</td>
    <td>Admin Support</td>
  </tr>
  <tr>
    <td>pdeford@jhu.edu</td>
    <td>ohmiyajohn@gmail.com</td>
    <td>acsutton@brandeis.edu</td>
    <td></td>
    <td>Justin.Payne@fda.hhs.gov</td>
    <td>khughitt@umd.edu</td>
    <td>Ben Busby</td>
    <td>Joanna Widzer</td>
  </tr>
  <tr>
    <td>baskine@mail.nih.gov</td>
    <td>octavio.juarez-espinosa@nih.gov</td>
    <td>mayars169@gmail.com</td>
    <td>nicolas.vince@nih.gov</td>
    <td>nbihlme1@jhmi.edu</td>
    <td>paiyeta1@jhu.edu</td>
    <td>Lisa Federer</td>
    <td>Lindsay Williams</td>
  </tr>
  <tr>
    <td>imisner@umd.edu</td>
    <td>russdurrett@gmail.com</td>
    <td>neranjan@gsu.edu</td>
    <td>clowen@email.gwu.edu</td>
    <td>michael.panciera.work@gmail.com</td>
    <td>usevani@nygenome.org</td>
    <td>Morty Abzug</td>
    <td></td>
  </tr>
  <tr>
    <td>allisondennis717@gmail.com</td>
    <td>pcantalupo@gmail.com</td>
    <td>yuewang1@mail.med.upenn.edu</td>
    <td>segun.jung@northwestern.edu</td>
    <td>zyu9@jhmi.edu</td>
    <td>eric.polley@nih.gov</td>
    <td>Sean Davis</td>
    <td></td>
  </tr>
  <tr>
    <td>leskomw@ncbi.nlm.nih.gov</td>
    <td>Allissa Dillman</td>
    <td>ye.chen@nih.gov</td>
    <td>zmartine@gmail.com</td>
    <td>ryamashi@ncbi.nlm.nih.gov</td>
    <td>dalerr@niddk.nih.gov</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>tan@ciwemb.edu</td>
    <td></td>
    <td>wagner@ncbi.nlm.nih.gov</td>
    <td>wongfay0207@hotmail.com</td>
    <td></td>
    <td>John.Simmons@nih.gov</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Greg Boratyn</td>
    <td></td>
    <td></td>
    <td>vlaufer@uab.edu</td>
    <td>lewisg@ncbi.nlm.nih.gov</td>
    <td>michalowski.d@gmail.com</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>carlosborroto@genepeeks.com</td>
    <td>hanl@ncbi.nlm.nih.gov</td>
    <td>stineaj@ncbi.nlm.nih.gov</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>erinkwagner1@gmail.com</td>
    <td></td>
    <td>jkeats@tgen.org</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>ericweitz.nih@gmail.com</td>
    <td></td>
    <td>wongfay0207@hotmail.com</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>hling1@jhmi.edu</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>
knwill01@gmail.com</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>Wendy Rubinstein</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


Amazon Web Services (AWS) usage instructions. 

* All persons with Github accounts **and** SSH keys on Aug 2nd should be able to log into the server for their team listed in the third column, below. The username is **ubuntu**.

* This also means that you can log into other team’s servers and that you share the same username/permissions with your team members. **Please be careful.**

* Using the same username/permissions makes it easy to share files, but easy to interfere with each other’s work. It is **strongly recommend** that once you login, you create a distinct working directory (suggestion: your Github username) to do you work. I.e.,: *mkdir -p myusername ; cd myusername ; git clone [...]*

* Code collaboration will be through Git & Github which makes coordinating and consolidating different directories and remote repositories (Github pages) easy. At least once you get the hang out it. You can ‘push’ from your personal working directory to Github and another team-member can immediately ‘pull’ your changes.

* A manifest of the installation software, versions and locations, is at [https://docs.google.com/document/d/1NosqSjeRUktfic6yS3lw8XJoq_WgvGNeM2b-D3SilAU/edit?usp=sharing](https://docs.google.com/document/d/1NosqSjeRUktfic6yS3lw8XJoq_WgvGNeM2b-D3SilAU/edit?usp=sharing) - however all the installed software should be already in your *PATH*.

Team structure and infrastructure (Github & AWS server)

<table>
  <tr>
    <td>RNAseq</td>
    <td></td>
    <td>IP</td>
    <td>Github repo</td>
  </tr>
  <tr>
    <td></td>
    <td>Homogenous mapping of all human RNAseq reads
</td>
    <td>ec2-52-2-m
ec2-52-2-15-150.compute-1.amazonaws.com</td>
    <td>https://github.com/DCGenomics/rnaseq_mapping_hackathon_v002 
git@github.com:DCGenomics/rnaseq_mapping_hackathon_v002.git</td>
  </tr>
  <tr>
    <td></td>
    <td>Comparison tool for 
human RNAseq reads
</td>
    <td>ec2-52-2-107-18.compute-1.amazonaws.com</td>
    <td>https://github.com/DCGenomics/rnaseq_comparison_hackathon_v002 
git@github.com:DCGenomics/rnaseq_comparison_hackathon_v002.git</td>
  </tr>
  <tr>
    <td></td>
    <td>cluster hosts for mapping</td>
    <td>54.86.30.181   cluster1 ec2-54-86-30-181.compute-1.amazonaws.com   cluster1
54.208.111.168 cluster2 ec2-54-208-111-168.compute-1.amazonaws.com cluster2
52.3.204.60	cluster3 ec2-52-3-204-60.compute-1.amazonaws.com	cluster3
54.175.253.16  cluster4 ec2-54-175-253-16.compute-1.amazonaws.com  cluster4
54.174.228.219 cluster5 ec2-54-174-228-219.compute-1.amazonaws.com cluster5
54.174.152.171 cluster6 ec2-54-174-152-171.compute-1.amazonaws.com cluster6


cluster1
54.86.30.181
cluster2
54.208.111.168
cluster3
52.3.204.60
cluster4
52.3.204.60
cluster5
54.174.228.219
cluster6
54.174.152.171
</td>
    <td>You can connect via "ssh cluster1", “ssh cluster2”, etc., from the main node ec2-52-2-15-150.compute-1.amazonaws.com</td>
  </tr>
  <tr>
    <td>Variation
</td>
    <td></td>
    <td>IP</td>
    <td>Github</td>
  </tr>
  <tr>
    <td></td>
    <td>Multiple myeloma clustering team
dbGaP usability script subteam

</td>
    <td>ec2-52-2-249-18.compute-1.amazonaws.com - NOW 40 vCPU, 160GiB of RAM - SSH host keys changed. You can delete the old one from ~/.ssh/known_hosts or run:

# ssh -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no ec2-52-2-[....]

ec2-54-208-251-34.compute-1.amazonaws.com - DALER BUILDHOST</td>
    <td>https://github.com/DCGenomics/multiple_myeloma_rnaseq_drug_response_hackathon_v002
git@github.com:DCGenomics/multiple_myeloma_rnaseq_drug_response_hackathon_v002.git</td>
  </tr>
  <tr>
    <td></td>
    <td>Myeloma CLUSTER</td>
    <td>Use the 172.16. address to copy files between instances.
ec2-52-6-6-8.compute-1.amazonaws.com / 172.16.242.161
ec2-54-210-74-208.compute-1.amazonaws.com / 172.16.242.162</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>The variant interpreter super team! (formerly the variant scanning and push button .vcf team).  
The cell type classification subteam (which will work with homogenous mapping)</td>
    <td>ec2-52-3-8-116.compute-1.amazonaws.com</td>
    <td>https://github.com/DCGenomics/NCBI_August_Hackathon_Push_Button_Genomics_Solution
git@github.com:DCGenomics/NCBI_August_Hackathon_Push_Button_Genomics_Solution.git</td>
  </tr>
  <tr>
    <td>Democratization of Bioinformatics
</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>The Educational Experience Team
The Vm library subteam
</td>
    <td>ec2-54-84-228-218.compute-1.amazonaws.com

ec2-54-164-126-108.compute-1.amazonaws.com - BUILDHOST for AMI creation on Wednesday.

ec2-52-2-145-47.compute-1.amazonaws.com - BUILDHOST for AMI - m4.4xlarge (16 vCPU, 60 GiB RAM, R-3.2.1 in PATH</td>
    <td>https://github.com/DCGenomics/ngs_education_hackathon_v002
git@github.com:DCGenomics/ngs_education_hackathon_v002.git</td>
  </tr>
  <tr>
    <td></td>
    <td>The SEQR team
</td>
    <td>ec2-54-174-135-198.compute-1.amazonaws.com</td>
    <td>https://github.com/DCGenomics/seqr_hackathon_v002
git@github.com:DCGenomics/seqr_hackathon_v002.git</td>
  </tr>
</table>


