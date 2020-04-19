# #carehacktCORONA

### THE PROBLEM (for the German Red Cross - Deutsches Rotes Kreuz)

In times of crisis, the task force of the DRK BaWü processes and prepares incident reports from up to 34 district associations. This is currently done manually. Each district unit sends a daily incident report on the number of personnel and material and its current activities in the fight against Corona. These incident reports are evaluated message by message by the operational staff of the task force and then transferred to an Excel spreadsheet to be up-to-date. On this basis, graphics with high operational value are then created. The information is essential for ensuring that the task force works efficiently, as it is the basis for decision-making and promotes transparency and communication within the organization. The constantly increasing complexity of this data poses increasing challenges for the task force in terms of evaluation.

### THE SOLUTION 

The main benefits of the solution:

- [x] **automation** of previous manual activities, including the visualisation of the results
- [x] **instant implementation** of stages 1 and 2 possible, as they fit seamlessly into the existing process 
- [x] **scalable approach** can be applied to almost all processes involving structured, repetitive and time-consuming tasks
- [x] **purchase costs** are low and the monthly operating costs are relatively easy to estimate
- [x] **state-of-the-art technologies** used like Tableau, Blue Prism software robots, cloud data storage



The solution designed and developed includes **three modular stages**: 

In **stage 1**, data from the incident reports sent daily by each district by e-mail to the Task Force of the DRC BaWü are automatically read (via the software robot Blue Prism) and integrated into a central Excel document. The provision of the information by the end user (district associations) remains unaffected, but the workload of the task force and administrators is significantly reduced as the data processing is executed automatically by the software robot.

For **stage 2**, a web-based visualisation technology (Tableau Public) is used to make the reactive graphical evaluation within the Excel sheet more efficient. The visualisation provides the current status graphically and is available to all relevant user of the DRK-organisation in real time via a web address. A first representation is available under the public version, visit https://public.tableau.com/profile/nils7887#!/vizhome/DRK_Hackaton_15872983224980/AktuellCOVID19Einsatzabschnitte?publish=yes

![image](https://user-images.githubusercontent.com/48921737/79688013-6eb90a00-824b-11ea-9ddd-8c7c9f29112b.png) 

**Stage 3** as a cloud-based ERP system is a rather medium-term holistic solution. The input behavior of the district associations and therefore the process workflow has to be adapted. A cloud-based database will be used instead of the Excel file. As a replacement for the previous pdf form, the user (district associations) enters the incident reports of his district via a web interface (frontend). The new information is stored as new data directly in the database. The BI tool tableau linked to the database processes the data and provides the information and visualisations in real time to a Web address. The graphic representation on the web address gives a clear picture of the current situation in terms of personnel, material and activities from the federal and state level down to the details of the district associations. 

--

### Stakeholder and project contributors
Nabila Munz   (Sponsor of the problem representing the German Red Cross)
Kevin Kampa   (Stage 1: Automation - Data extraction of pdf)
Hoai-Anh Ngo  (Stage 1: Automation - Data integration to excel spreadsheet)
Isabel Zani   (Stage 2: Visualisation - Tableau to excel and database)
Michael Hagen
Masood Ahmed 
Svetoslava Hristova
