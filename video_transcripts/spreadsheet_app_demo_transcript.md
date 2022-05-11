* Researchers often use spreadsheets to detail experiments.
* Yet researchers are burdened by inefficient use of spreadsheets.A common challenge is redundant information that result from using a single spreadsheet to originate different entities.
* Further, spreadsheets are complicated when researchers use columns for multiple purposes. 
  * Columns may guide capturing information about a sequence of activities.
  * Simultaneously, columns may guide capturing information about a single entity.
* This design limits researchers by requiring redundant entries.
* Also, the design poses challenges when researchers change the sequence of activities.
* The spreadsheet application of LiteLIMS reenvisions spreadsheets to address these challenges.
* Our design includes five Sheets that enable capturing conceptual entities, physical material, planned processes, reporting workflows and executed processes.
* In the conceptDefinition Sheet, researchers may describe experiments with a variety of conceptual entities.
* Notably, researchers may register catalog numbers to generate a catalog of common material. 
* Researchers may use the materialDefinition Sheet to identify material with lot numbers and detail material with catalog numbers.
* The conceptDefinition and materialDefinition Sheets together support capturing metadata about material in a non-redundant fashion.
* To describe laboratory activities, researchers must use the processDefinition Sheet to define a bank of planned processes.
* A planned process includes standard parameters and its values.
* Researchers may use the workflowManagement Sheet to define reporting workflows, which are sequences of processes.
* Reporting workflows aid in consistently and flexibly reporting laboratory activities when they are populated in the processExecution Sheet.
* This Sheet is used to describe laboratory activities. Here, the rows guide researchers through a sequence of processes while the columns guide researchers through a single activity.
* The design of our five Sheets simplifies capturing complex metadata and enables recursively retrieving the history of material.
* These capabilities are aided by key features.The column visibility feature reveals only columns relevant to the entity being entered. 
* This prevents navigating a multitude of columns while minimizing the number of spreadsheets.
* Mini tables enable accurately reflecting one-to-many relationships with reduced redundancy. 
* Here, the parent is reflected on the top row along with the first child. All subsequent children are entered below the row containing the parent.
* The cell background is used to reflect required, optional and completed fields as red, orange, and yellow, respectively. 
* For mini tables, the background of the top row is displayed in the standard shade, while subsequent rows are displayed in a lighter shade.
* To prevent unwanted transformations to entries, each column contains both value formatting and data validation. 
* Our combination of five Sheets and its features enable efficient use of spreadsheets for capturing complex information about experiments.