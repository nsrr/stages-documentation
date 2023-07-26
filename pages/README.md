# About

The Stanford Technology Analytics and Genomics in Sleep (STAGES) study is a prospective cross-sectional, multi-site study involving 20 data collection sites from six centers including Stanford University, Bogan Sleep Consulting, Geisinger Health, Mayo Clinic, MedSleep, and St. Luke's Hospital. The project has collected data on 1,500 adult/adolescent patients evaluated for sleep disorders, including:

- Objective nocturnal sleep polysomnography (PSG) recordings (EEGs, chin and leg EMGs, nasal and oral breathing, chest movements, leg movements, position, EKG). This is the gold standard for sleep evaluation in sleep clinics.
- Comprehensive subjective sleep symptoms assessment through an on-line sleep questionnaire called the Alliance Sleep Questionnaire (ASQ, developed over 5 years by 5 academic institutions). The questionnaire also includes key medical history questions.
- Continuous actigraphy over several weeks to get untransformed activity counts (a Huami/Xiaomi actigraph device has been identified and validated against PSG and clinical gold standard Actiwatch)
- 3-D facial scans to extract craniofacial features predictive of sleep apnea (*not available on NSRR*)
- On-line neuropsychological assessments and psychovigilance tests (impact of sleep disorders)
- Medical record data (*not available on NSRR*)

All data, samples, analytic tools, and supporting documentation will be made publicly available for use by any interested researcher, provided a request is submitted to the National Sleep Research Resource and approved.

The National Sleep Research Resource is grateful to the STAGES team for sharing these data.

## Data preamble and access restrictions

The STAGES dataset is available for non-commercial and commercial use.

## Citation and acknowledgement

When using this dataset, please cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

Please include the following in the author line of publications and presentations:

> ... and the STAGES cohort investigator group.

Please include the following text in the Acknowledgements:

> This research has been conducted using the STAGES - Stanford Technology, Analytics and Genomics in Sleep Resource funded by the Klarman Family Foundation. The investigators of the STAGES study contributed to the design and implementation of the STAGES cohort and/or provided data and/or collected biospecimens, but did not necessarily participate in the analysis or writing of this report. The full list of STAGES investigators can be found at the project website.
>
> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Data overview

**[/datasets](:files_path:/datasets)** <br/> Data from the Alliance Sleep Questionnaire (ASQ). The NSRR team processed parts of the original ASQ data into <a href="https://github.com/nsrr/stages-data-dictionary" target="_new">a Spout data dictionary</a>. Users can browse [available variables and their distributions here](https://sleepdata.org/datasets/stages/variables/).

**[/original](:files_path:/original)** <br/> Data and documentation as received from the STAGES group. Includes polysomnography (EDF), questionnaire, medication, and other data. **Everything in this folder is provided "as-is".**

## Protocols and manuals

- [STAGES Manual of Procedures (PDF)](:files_path:/documentation/STAGES MOP 2018-08-09.pdf)

## Changelog

*July 2023*
- Add note in About section about unavailability of facial scan and medical record data

*June 2023*
- Remove PSGs from Mayo Clinic site due to EDF/annotation conversion issues. The NSRR recommends not using Mayo Clinic PSG data until they are reprocessed by the STAGES data contributor at a later date.

*July 2021*
- STAGES dataset published to sleepdata.org
