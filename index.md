# Testing non-standard neutrino interactions in (anti-)electron disappearence experiments

In this repository you can have acess to all codes needed to simulate the results of [arXiv:2106.15725](https://arxiv.org/abs/2106.15725).

![Image](logo-gefan.png)

## Non-standard neutrino interactions in the neutrino production and detection

The analysis of this work, is dependent on six free paramters: the mixing angles 13 and 12, the mass square differences 21 and 31, 
the real and imaginary part of a non-standard interactions coupling. We divide the analysis in four independent analysis, for tensor and scalar interactions, where for each case were considered <img src="https://render.githubusercontent.com/render/math?math=[\tilde{\epsilon}_X]_{e\mu}"> or <img src="https://render.githubusercontent.com/render/math?math=[\tilde{\epsilon}_X]_{e\tau}">.

## The number of events

### Daya Bay
In order the simulate the number of events of Daya Bay, one should acess the "events/dayabay/" folder and use the following commands:
```markdown
make
./glf_spectrum
```
a .csv file will be generated containing the energy and the ratio of events for each energy bin. To visualize the number of events, one should use
```markdown
python3 events.py
```
### Double Chooz
In order the simulate the number of events of Double Chooz, one should acess the "events/doublechooz/" folder and use the following commands:
```markdown
make
./glf_spectrum
```
a .csv file will be generated containing the energy and the ratio of events for each energy bin. To visualize the number of events, one should use
```markdown
python3 events.py
```
### RENO
In order the simulate the number of events of RENO, one should acess the "events/reno/" folder and use the following commands:
```markdown
make
./glf_spectrum
```
a .csv file will be generated containing the energy and the ratio of events for each energy bin. To visualize the number of events, one should use
```markdown
python3 events.py
```
### KAMLAND
In order the simulate the number of events of Kamland, one should acess the "events/kamland/" folder and use the following commands:
```markdown
make
./glf_spectrum
```
a .csv file will be generated containing the energy and the ratio of events for each energy bin. To visualize the number of events, one should use
```markdown
python3 events.py
```

### SOLAR NEUTRINOS

## The statistical analysis

### Medium baseline reactors

### Long baseline reactors

### Solar experiments

## Combining the experiments

### Solar experiments + KAMLAND

### Global analysis

## Support or Contact

You can contact us: mchaves@ifi.unicamp.br, orlando@ifi.unicamp.br and holanda@ifi.unicamp.br
