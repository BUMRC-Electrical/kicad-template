<!-- kicad_template/README.md -->

<div align="center">
    <img src="/img/mrc.jpeg" width="200">
</div>

# BU Mars Rover Club Electrical Team KiCad 10.0 Project Template

This repository is a template for the electrical team to use for board design. It can be easily cloned, edited, and uploaded to the club github for collaboration between members.

## File Structure

- ```/kicad/``` contains all of the KiCad 10.0 project files
- ```/datasheets/``` should contain all of the .pdf files for the important components
- ```/calculations/``` should include any significant calculations that led to a component choice or value choice

## Using this Template in KiCad 10.0

Download KiCad [here](https://www.kicad.org/download/). We are using version 10.0 for the club this year.

1. Click the ```Use this Template``` to make a personal copy of this repository.

2. Set the repository name to your desired name: PROJECT_NAME

3. Open up KiCad 10.0 and open the default project in the ```kicad/default``` directory.

4. Click ```save as``` and save it to the ```kicad``` directory under your desired name PROJECT_NAME.

5. The folder tree should look like this:

```
PROJECT_NAME/
├── kicad/
│   ├── default/
│   │   ├── mrc_template.kicad_dru
│   │   ├── mrc_template.kicad_pcb
│   │   ├── mrc_template.kicad_pro
│   │   ├── mrc_template.kicad_sch
│   │   └── sheet.kicad_wks
│   └── PROJECT_NAME/
│       ├── PROJECT_NAME.kicad_dru
│       ├── PROJECT_NAME.kicad_pcb
│       ├── PROJECT_NAME.kicad_pro
│       ├── PROJECT_NAME.kicad_sch
│       └── sheet.kicad_wks
├── datasheets
├── calculations
├── img
├── README.md
└── LICENSE
```

5. Delete the ```kicad/default``` directory.

6. Open up your newly renamed project, ```PROJECT_NAME.kicad_pro```, and then open the schematic editor.

7. Click ```File -> Schematic Setup```, then under ```Project -> Text Variables```, populate all of the fields with the correct information such as ```contributors``` and board ```revision```. Then click OK and you should see the bottom right of the schematic and layout correctly update. See a screenshots below:

<br>

<div align="center">
    <img src="img/text_variables.png" width="500" max-height="400">
    <img src="img/fields.png" width="500" max-height="400">
</div>

<br>

8. Edit this README.md file, initialize the git repository, and start working on your project!
