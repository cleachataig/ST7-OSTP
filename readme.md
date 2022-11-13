<p align="center">
    <img width="150" src="https://decisionbrain.com/wp-content/uploads/2019/04/DB-Logo-New-Slogan.png" alt="logo">
</p>
<h2 align="center">ST7-OSTP - Daily planning of a moving team</h2>

---

## 🔎 Description

DecisionBrain is a start-up that develops optimisation and decision support solutions for logistics, industry, workforce planning and supply chain on all continents. In the context of a mission carried out for a client, we intervened to carry out part of the project: a planning tool for a team of mobile technicians to create the daily rounds of 500 technicians who must carry out some 10,000 tasks. 

## 📚 Description

More information about the first project milestone is available [here](Jalon1/readme.md).

More information about the second project milestone is available [here](Jalon2/readme.md).

More information about the third project milestone is available [here](Jalon3/readme.md).

## 🚗 Usage

1. You can first install a new virtual environment with the required python packages using the line `conda env create -f environment.yml` in your terminal, and activate it with `conda activate decisionbrain`
2. Then create an empty directory `data` in the home directory
3. Extract `InstancesV1.zip` to `InstancesV1` in the directory `data`
4. Extract `InstancesV2.zip` to `InstancesV2` in the directory `data` 
5. Extract `InstancesV3.zip` to `InstancesV3` in the directory `data`
6. Your project should look like this

```bash
|-- data
|    |-- InstancesV1
|         |-- InstanceBordeauxV1.xlsx
|         |-- ...
|    |-- InstancesV2
|         |-- InstanceBordeauxV2.xlsx
|         |-- ...
|    |-- InstancesV3
|         |-- InstanceColumbiaV3.xlsx
|         |-- ...
|
|-- Jalon1
|    |-- Solutions
|         |-- Map
|         |-- Text
|         |-- Timetable
|    |-- ...
|
|-- Jalon2
|    |-- Solutions
|         |-- Map
|         |-- Text
|         |-- Timetable
|    |-- ...
|
|-- Jalon3
|    |-- Solutions
|         |-- Map
|         |-- Text
|         |-- Timetable
|    |-- ...
|
|-- .gitignore
|-- readme.md
|-- environment.yml
|-- DecisionBrain_Report_Grp5.pdf
|-- Slides_Grp5.pdf
```

7. You should now be able to run any Jupyter Notebook of the `Jalon1`, `Jalon2`or `Jalon3` directories
8. You can find additional information on the project in the pdf files `DecisionBrain_Report_Grp5.pdf` and `Slides_Grp5.pdf`. 