Tool/Model Version: gemini(2.5 Flash), perplexity AI(GPT-4 )

What I Asked For:
I asked for assistance in resolving a number of Rosalind programming issues.  These included working with DNA, RNA, and protein sequences, parsing FASTA files, calculating the GC content and using Python to convert RNA to protein and have also used for the initial tasks where it was asked to use gemini to get examples which helps in understanding the concepts better.

Prompt Snapshot:

"Given are DNA sequences in FASTA format, find the one with the highest GC content."

"Modify the script to print GC content for each sequence."

"Translate RNA string to protein using the codon table."

What I Changed Before Committing:
I modified string splitting and parsing techniques to accommodate various input formats.  For efficiency, I used Python's count() method instead of some counting techniques.  I ensured that the outputs were formatted precisely as Rosalind requested, paying particular attention to line order and decimal accuracy.

How I Verified Correctness:
I ran the code on Rosalind's datasets and confirmed the output matched the expected results.
