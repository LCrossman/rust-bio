<b>micro-biorust Project Roadmap</b>


<b>Introduction</b>
<p>This Roadmap outlines planning features, and milestones for bioinformatics Rust functions aimed at the Microbiology community for whole genomes, transcriptomes and metagenomics</p>

<b>Goals and Objectives</b>
- Add new features specifically aimed at Microbiological genomics and metagenomics
- Update and enhance usability for that community

<b>Milestones</b>

Short-term (next 3 months)
Integrate current functions, document and write tests for:
- genbank parser - convert gbk to DNA fasta, convert gbk to protein fasta
- embl parser - convert embl to DNA fasta, convert embl to protein fasta

Medium-term (next 6 months)
Write functions and tests to genbank parser conversion for:
- convert gbk to gff
- convert embl to gff
- gff parsers to enable conversion to DNA fasta & protein fasta

Longer-term (Next 12+ months)
- speeding up for scale - forgotten but useful functionality
- planning for next steps 