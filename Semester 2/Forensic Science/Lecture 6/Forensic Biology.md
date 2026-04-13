# The Three W's of Forensic Biology
## What?
Are we looking at body fluid, DNA, Etc.
## Who?
Who's is it, Are they a suspect, what can we derive from this information
## How?
How was it retrieved? How is it significant? How can it be useful?

# Examples of fluids we could encounter
## Blood
Chemical blood tests include the:
- Kastle-Meyer (Presumptive, Screening)
	- This identifies the hemoglobin's peroxidase-like activity
	- Add reagent + hydrogen peroxide
	- If blood is present it turns bright pink
	- ❌==BUT== Very sensitive to bleach, some metals and plant peroxidases
- Hemastix (Presumptive)
	- Reacts with hemoglobin to turn tests strip from yellow to green/blue
	- ✔Fast and easy
	- ❌==BUT== Same false positives as Kastle-Meyer
- Luminol (Presumptive + Search tool)
	- Reacts with Iron in Hemoglobin
	- Spray in dark -> Blue glow (chemiluminescence)
	- ✔Detects trace blood
	- ✔Detects even after washing
	- ❌==BUT== Can react with bleach/copper
	- ❌==BUT== Can dilute DNA if overused
**We are looking for the Hemoglobin**

## Semen
Acid phosphatase test (Presumptive test)
- Detects Acid Phosphatase enzyme (very high in semen)
- Add reagent -> purple colour change (rapid = strong positive)
- Quick screening
- Not specific (Some other fluids have AP, just lover levels)

Spermatozoa (Confirmatory test)
- Staining +microscope -> look for:
	- head
	- midpiece
	- tail
- ✔ Highly specific -> Confirms semen
- ❌May fail if no sperm present or its a degraded sample

## Saliva
The Phadebas test (Presumptive test)
- Used to identify saliva on fabrics and other materials.
- It works by identifying the levels of α-amylase (breaks down starch -> sugars)
- An enzyme present in saliva

- Using a tablet made of starch + blue dye
- If amylase is present it breaks down the starch and releases the blue dye
- Blue color = positive for saliva

- ✔Saliva has very high amylase
- ✔Good for
	- Bite marks
	- Envelopes
	- Cigarettes
	- Drink containers
- ❌Other fluids contain amylase but have tiny amounts
	- Sweat
	- Urine
	- Some plants

# DNA
- Unique and inherited
- Found in all biological specimens containing nucleated cells
- Cell-to-cell DNA is identical
- No 2 individuals (except identical twins) have exactly the same DNA
	- >99% of our DNA is identical
	- <1% is different
- Very stable
- Analysis of small biological specimens is possible

## Short Tandem Repeats (STRs)
STRs = short DNA sequences (2-6 bases) That repeat over and over
Showing 7 repeats vs 8 repeats

- Number of repeats varies between people
- Different number of repeats = different Alleles

At each STR location (locus), you get:
- One allele from mom
- One allele from dad
- You might see
	- 7, 8
	- 10, 10
	- 12, 14

Each "peak" in a graph = an STR allele (repeat number)
So:
Peak at "8" = 8 repeats
Peak at "12" = 12 repeats

- ✔Good for identification
- ✔Work with degraded DNA
- ✔Some loci used worldwide (e.g., CODIS markers)

# DNA Analysis
1. Extraction
2. Quantization
	1. Too little DNA -> STOP
	2. Sufficient DNA -> Continue
3. Amplification of Target regions
	- This means replicating the section you're studying a lot
4. Detection
	- DNA Profile

## DNA Profiles
This is an example of an electropherogram
Key features:
- Peaks -> Each peak is an allele
- Height -> amount of DNA (not identity)
- X - Axis
	- Represents allele size/repeat number
	- This is where you read values like 10, 11, 12, etc.
- Y- Axis
	- Signal intensity (RFU)
	- Higher peak = more DNA
- Loci Labels
	- Each section = a specific STR locus
![[Pasted image 20260325170024.png]]

## How to read a single profile
Case 1: One peak
- Homozygous
	- Example: 12 -> Means 12, 12

Case 2: Two peaks
- Heterozygous
	- Example: 10 and 12 -> means 10, 12

Peaks are just a visual way of showing numbers
E.g.:
- Peak -> 10
- Peak -> 12
- Output -> 10, 12

## Comparing 2 people
Person A -> 10, 13
Person B -> 10, 15

Output -> 10, 13, 15
This is a ==Mixture==
Because more than 2 numbers at a locus

**SO**
Evidence:
10, 12

Suspect:
10, 12

Match?
✔ YES

---
Evidence:
10, 12

Suspect:
10, 15

Match?
❌ NO (15 doesn’t belong)

---
Evidence:
10, 13, 15

Suspect:
10, 15

Match?
 Can suspect be part of it?  
✔ YES (their numbers are present)

Suspect:
9, 15
Can suspect be part of it?  
❌ NO (9 is not in evidence)

ALL DNA PROFILE LOCI MUST MATCH TO MAKE AN IDENTIFICATION
---

# When to give up?
When the DNA profiles are so messy you can't confidently interpret the data
- Taking "Mixture" to a whole new level
![[Pasted image 20260325173527.png]]

- Too many contributors
- Overlapping alleles
- Low DNA quantity
- Degradation

# STRmix
A software system used to interpret complex DNA mixtures
- Uses statistics & probability models 
- Tests different contributor combinations
- Calculates likelihoods
- it gives "how likely someone is a contributor"

# Rapid Portable DNA
Machine that can generate a DNA profile on site without the need of a full lab

- Not suitable for complex or degraded samples
- Not great at mixtures
- Not always admissible
- Used mostly for screening

# Single Nucleotide Polymorphisms (SNPs)
A single base change in DNA
Example:
- Person 1 -> AATG
- Person 2-> AACG
	Just one letter difference

Compare STRs and SNPs

| STRs                     | SNPs                     |
| ------------------------ | ------------------------ |
| Repeats (e.g., AATG x10) | Single letter change     |
| Highly Variable          | Less variable            |
| Used for ID              | Used for traits/ancestry |
- Give biological information, not ID

## What can SNPs tell us?
The **predict** traits
- Eye color
- Hair color
- Ancestry
- Building biological profile

## HirisPlex
- DNA prediction system that uses SNPs to predict:
	- Eye colour
	- Hair colour
- Looks at specific SNP markers
- Theses are linked to traits like:
	- blue vs brown eyes
	- Blonde vs dark hair

## DNA Phenotyping with Parabon Snapshot
Creates a predicted image using SNPs from a crime scene
predictions of:
- Genetic ancestry
- Eye color
- Hair colour
- Skin Colour
- Freckling
- Face Shape
- Kinship

## GEDmatch
Public genealogy DNA database
people upload DNA from:
- 23andMe
- AncestryDNA

Forensic scientists can use these databases to create a family tree and find relatives

---
# Identical Twins Problem
Twins have the same DNA
- DNA sequencing can't tell them apart

## Deep Genome Sequencing
Looks at tiny mutations that happen over time
Develop small genetic differences

---
# Non-Human DNA
We have:
- Animal DNA
- Plant DNA
- Microbial DNA

Other DNA can:
- Dog hair links suspect to scene
- Pollen links suspect to location
- Food traces connect events

---
# Incidental Findings
Testing DNA can lead to the discovery of:
- A familial relationship is wrong
- Hidden genetic condition
- Unknown relative

Can be sensitive
## Ethical Issues
1. Privacy
	- Who owns DNA data?
2. Consent
	- Did the person agree to this use?
3. Misuse
	- Insurance discrimination
	- Surveillance concerns
4. Family impact
	- DNA reveals info about relatives too

