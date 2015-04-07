# Bibtex Convention

## Conference Proceedings

```
@inproceedings{choi:13a,
	Author = {Choi, Jinho D. and McCallum, Andrew},
	Title = {{Transition-based Dependency Parsing with Selectional Branching}},
	Booktitle = {Proceedings of the 51st Annual Meeting of the Association for Computational Linguistics},
	Series = {ACL'13},
	Pages = {1052--1062},
	Year = {2013}}
```

|Field      |Convention|
|:----------|:---------|
|`Key`      | Last name of the first author + `:` + last two digits of the year + a distinct alpabet.|
|`Author`   | Last name`,` first name (middle initial), delimited by `and`.|
|`Title`    | The full title preserving capitalization, sounded by double curly brackets.|
|`Booktitle`| The full conference name (not the acronym such as "ACL").|
|`Series`   | The acronym of the conference + `'` + last two digits of the year.|
|`Pages`    | First page + `--` + last page.|
|`Year`     | The year in four digits.|

## Journal Articles

```
@article{palmer:05a,
	Author = {Palmer, Martha and Gildea, Daniel and Kingsbury, Paul},
	Title = {{The Proposition Bank: An Annotated Corpus of Semantic Roles}},
	Journal = {Computational Linguistics},
	Number = {1},
	Volume = {31},
	Pages = {71--106},
	Year = {2005}}
```

|Field      |Convention|
|:----------|:---------|
|`Key`      | Last name of the first author + `:` + last two digits of the year + a distinct alpabet.|
|`Author`   | Last name`,` first name (middle initial), delimited by `and`.|
|`Title`    | The full title preserving capitalization, sounded by double curly brackets.|
|`Journal`  | The full journal name (not the acronym such as "CL").|
|`Number`   | The number of the journal.|
|`Volumn`   | The volumn of the journal.|
|`Pages`    | First page + `--` + last page.|
|`Year`     | The year in four digits.|

## Technical Reports

```
@techreport{choi:12b,
	Author = {Choi, Jinho D. and Palmer, Martha},
	Title = {{Guidelines for the Clear Style Constituent to Dependency Conversion}},
	Institution = {University of Colorado Boulder},
	Number = {01-12},
	Year = {2012}}
```

|Field      |Convention|
|:----------|:---------|
|`Key`      | Last name of the first author + `:` + last two digits of the year + a distinct alpabet.|
|`Author`   | Last name`,` first name (middle initial), delimited by `and`.|
|`Title`    | The full title preserving capitalization, sounded by double curly brackets.|
|`Institution`| The name of the institution.|
|`Number`   | The number of the report.|
|`Year`     | The year in four digits.|

## Thesis

```
@phdthesis{choi:12c,
	Author = {Choi, Jinho D.},
	Title = {{Optimization of Natural Language Processing Components for Robustness and Scalability}},
	School = {University of Colorado Boulder},
	Year = {2012}}
```

|Field      |Convention|
|:----------|:---------|
|`Key`      | Last name of the first author + `:` + last two digits of the year + a distinct alpabet.|
|`Author`   | Last name`,` first name (middle initial).|
|`Title`    | The full title preserving capitalization, sounded by double curly brackets.|
|`School`   | The name of the school.|
|`Year`     | The year in four digits.|

## Notes

* Do not include any field other than the ones above for the brevity.
* Cite hyperlinks using `<footnote>`.
* Cite [arXiv](http://arxiv.org) papers using the technical report format.