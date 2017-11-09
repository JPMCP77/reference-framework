The First mile farm data model
============================

## Complete model in JSON

The model consists of the main data entities Group, Farmer, Farm, Plot, Cropobservation and number of supporting data entities. New data attributes or data entities can be added to the model by submitting extensions to the model.  

<script src="../_static/docson/widget.js" data-schema="../../_static/Firstmilefarmerdatab.JSON"></script>

## Flattened table in Excel format

A flattened table in excel format is avialable [here](https://docs.google.com/spreadsheets/d/1lmKCK8K4ZXjjW23dOeA7WtUf3QbyhKg3HWF_7StsAsY/edit?usp=sharing)


## Groups 

**Definition:** Loosely defined group of farmers. Farmers can be member of a cooperative or union, organized by a company as contract farmers or as part of a support program, etc. 

**Data atributes:**
Many attributes can be assigned to a group, depending on the nature of a group. Examples are the area of operation, the valid certifications from standard organisations, total amount of certified produce in stock. In core of data model  the reference framework for first mile farm data. The entity here is presented to demonstrate a coherent framework which is ready to be expanded or can customize depending on the requirements.

As explained in section 4.1.1 the block [GroupRecordGlobalID, GroupInternalID, GroupGeoID] provides the means to: 1 globally uniquely identify all the records of farmer groups, 2 to to provide each farmer group with a unique interal ID which allows to link to link other data entities to this farmer group and; 3 to have a clue to uniquely identify this farmer group in the field or to clean the dataset when combined with datasets from other sources.

Required data attributes are indicated by grey shaded fields in the table below.

<script src="../_static/docson/widget.js" data-schema="../schema/components/Group.JSON"></script>

