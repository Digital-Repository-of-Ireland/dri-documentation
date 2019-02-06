Reviewing and Publishing
=========================

This chapter describes how to review objects and publish collections. Publishing collections (i.e., making them publicly viewable) is a two step process.

Reviewing
----------

Setting the status of an object to *reviewed* indicates that editing of the descriptive metadata has been completed. Also that any attached assets are displaying correctly and all background processes have finished. Individual objects can be set as reviewed from the object Editor Tools menu (:numref:`fig-review-object` (1)).

.. _fig-review-object:
.. figure:: images/review_object.png
   :alt: Review object menu option

   Review individual object

Alternatively it is possible to set all draft objects contained within a collection and it's sub-collections to reviewed using the collection Editor Tools menu (:numref:`fig-review-coll` (2)). This section of the menu provides a summary of the number of sub-collections
and objects by status, either *draft*, *reviewed* or *published*.

.. _fig-review-coll:
.. figure:: images/review_collection.png
   :alt: Review collection objects menu

   Mark all objects as reviewed

Changing the status of the objects is carried out in a background process that could take some time to complete.
You should be able to see the status counts change from draft to reviewed as this process is running.

Publishing
-----------

The second step is to publish the reviewed objects. This operation can only be carried out by an Organisational or Collection Manager and must be done from the top level collection. This will publish all reviewed objects contained within the top level collection, including those in its sub-collections. If the status summary information shows that there are reviewed sub-collections and objects they can be published by pressing the publish button (:numref:`fig-publish` (1)). 

.. _fig-publish:
.. figure:: images/publish_collection.png
   :alt: Publish collection objects menu

   Mark all objects as published

Again this will be carried out in the background and depending on the number of objects could take some time to complete. 

Digital Object Identifier
-------------------------

As part of the publishing process of an object a `Digital Object Identifier (DOI) name <http://www.doi.org/hb.html>`_ for the object will be created in the `DataCite registry <https://search.datacite.org/>`_. When publishing is complete the DOI name will be visible in the object's citation. The DOI name and the metadata used to create it (a subset of the full object metadata) will be **permanently accessible** in the DataCite registry. As such it is important that an object is checked thoroughly prior to being published.

The following fields are used (if present) in the DOI name metadata:
 
 * Title 
 * Description
 * Creator
 * Creation Date
 * Published Date
 * Rights

Certain actions performed after an object has been published will result in a new DOI name being created. This will take the form of the previous DOI name with a version number appended, e.g. '-1', '-2', etc. These actions are:

 * Updating a collection's or object's metadata - Updating the title or creator field will result in a new versioned DOI name being created. Modifying any of the other fields listed above will result in the DOI name metadata being updated in the DOI system.
 * Adding or changing an object's asset - This will always result in a new versioned DOI name.

After a new versioned DOI name is created, the previous DOI name will still exist and be resolvable. It will now link to a page that lists the current and previous DOI names, along with the reason for each DOI name being created (e.g. metadata update).
