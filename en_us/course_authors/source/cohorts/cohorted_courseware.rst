.. _Cohorted Courseware Overview:


##########################################
About Cohorted Courseware
##########################################

If you have :ref:`cohort groups enabled<Enabling and Configuring Cohorts>` in
your course, you can design different course experiences for students in
different cohort groups. Design your course with different "tracks" of content
so that students in one cohort group are given different content than students
in another cohort group. You do this by creating content groups. For details
about content groups, see :ref:`About Content Groups`.

Follow these steps to set up cohorted content in your course. Optionally, you
might choose to transpose the order of steps 4 and 5.

#. :ref:`Enable cohorting for your course<Enabling and Configuring Cohorts>`.
#. :ref:`Assign students to cohort groups<Options for Assigning Students to
   Cohorts>`. 
#. :ref:`Create content groups in Studio<Creating Content Groups>`.
#. :ref:`Associate one or more cohort groups with a content group<Associate
   Cohort Groups with Content Groups>`. 
#. In your course outline, :ref:`specify
   which content groups can see each component<Specify Which Groups Can See Which
   Components>`. 
#. Preview the courseware for each content group/cohort group.
   

.. _About Content Groups:

*******************************
Content Groups Overview
*******************************

You use content groups to specify the content that a particular cohort group
or groups will see in your course. Each component in your course can be made
visible to one or more content groups. If no content group is specified for a
component in a course that has cohort groups enabled, then it is visible to
all students enrolled in the course, regardless of the cohort group they
belong to.

You can designate one or more cohort groups of students to be associated with
a content group. For example, you design your course to have 2 content tracks,
so you create 2 content groups, one called "Track 1" and the other called
"Track 2". You have 4 cohort groups in your course, A, B, C, and D. You decide
that Cohort Groups A, B, and C will be assigned to Track 1 content, while
Cohort Group D is assigned to Track 2 content.

.. _Creating Content Groups

*********************
Create Content Groups
*********************

#. In Studio, select **Settings** then **Group Configurations**.
#. On the **Group Configuration** page, select **New cohorted content group**.
#. Enter a meaningful name for the content group, then click **Create**.
#. Repeat this step as necessary to create all the content groups you want.

After you create a content group, you can associate one or more cohort groups
to this content group, or work with your course outline to specify which
components are designated for which content group.

For details, see :ref:`Associate cohort groups with content groups` and
:ref:`Specify Which Groups Can See Which Components`.


.. _Associate Cohort Groups with Content Groups

************************************************
Associate Cohort Groups with Content Groups
************************************************

After you have created content groups, you associate one or more cohort groups
with them, to specify which student cohorts can see which content in your course.

#. In the LMS, select **Instructor**, then select **Membership**. 
   
#. Scroll to the **Cohort Management** section at the bottom.

#. Select a cohort group from the drop down list. You see the details of the
   selected cohort group.
   
   If the cohort groups that you want to associate with your content groups do
   not yet exist, you can create them here.
   
4. Click the **Settings** tab for the selected cohort group and select the
   **Associate this cohort group with a cohorted content group** option.

#. Select the content group from the drop down list.
#. Click **Save**.
   
   You have associated a cohort group with a content group. Any course content
   that you designate as visible to that content group is visible to students
   in the associated cohort group. 

You can associate additional cohort groups to the same or another content group by
repeating steps 3 to 6.


.. _Specify Which Groups Can See Which Components

***********************************************************
Specify Which Groups Can See Which Components in Courseware
***********************************************************

After you have created at least one content group, you can edit your course in
Studio and designate whether all students, or particular content groups, can
view each component.

.. note:: Components that you do not explicitly indicate as visible to a group
   are visible to all students enrolled in your course, regardless of the
   cohort group that they belong to.

#. In Studio, select **Content**, then select **Outline**. 
#. For each component that you want to make visible only to a particular content group or groups, click the **Visibility Settings** icon.
#. In the **Editing visibility** dialog, select **Specific Content Groups**, then select the checkbox for each content group to which you want the current component to be visible.
#. Click **Save**.

.. note:: If some content in the current course section is visible only to particular groups, you see a note in the sidebar indicating this. 


.. _View Course as a Content Group

*********************************************
Preview Course as a Member of a Content Group
*********************************************

After you designate components in your course as being visible to only
specific content groups, you can preview your courseware to ensure that each
group correctly sees the intended content.

#. In Studio, in the course outline, click **Preview Changes**.
#. You see your course section in the **Courseware** section of the LMS. In the navigation bar at the top of the page, select one of the options in the **View this course as** drop down list:
   * Staff -- sees all content in the course.
   * Student -- sees any content that is set to be visible to all students.
   * Student in <name of content group> -- sees the course as a member of the specific content group.
     
