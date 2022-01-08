# SNOW-CSA-1-User-Interface-and-Navigation

## Free Personal Developer Instance
https://developer.servicenow.com/dev.do

Online Guide
https://developer.servicenow.com/dev.do#!/learn/learning-plans/rome/new_to_servicenow/app_store_learnv2_buildmyfirstapp_rome_personal_developer_instances

## ServiceNow CSA 
https://www.servicenow.com/content/dam/servicenow/other-documents/training/servicenow-sys-admin-exam-specs.pdf

## Part 1: User Interface & Navigation
- ServiceNow Overview
- Lists and Filters
- Forms and Templates
- Branding

## There are three components of the ServiceNow user interface:
- Banner
- Application Navigator
- Content Frame

## Lists
A list is a content page displaying zero or more records from the same table. Rows and columns organize the list. Each row is a record and each column is a field from the record. Lists are:

- Searchable: Enter a value in the Search field
- Sortable: Click the column label
- Editable (if permissions allow): Double-click a field value

## Filters
Filters determine which table records are displayed in a list. When a developer creates a list module, the filter conditions are set. In the example, only records with the Active field value of true appear in the list. The syntax All > Active = true is known as a breadcrumb.

To remove a condition from the breadcrumbs, click Remove next condition (>) to the left of the condition to be removed. For example to remove the Active = true condition, click the > between All and Active = true.

## Forms
A form is a content page displaying fields and values for a single record from a database table. Forms have a 1-column layout, a 2-column layout, or a mix of both. Forms are opened from modules in the Application Navigator or by clicking a record's number in a list.

### Section
Forms may contain Sections. Sections are logical groupings of fields. In the baseline case, sections are rendered as tabs at the bottom of a form. The use of sections prevents users from having to scroll through long forms. Using a script, sections can be hidden when they are not needed.

### Views
Forms can have multiple views. A view is an alternate layout for presentation of a record's data. Different user profiles use different views to see data from the same record. ServiceNow has a special view called the Self Service view. Self Service users do not require a ServiceNow license in order to see a record's form.

The view name appears on a form's header. If there is no view name in the form header, the view is the Default view.

To change views:

Click the Additional actions menu (the Menu is a trigram) and select the View menu item.
Select a view.

### Annotations
Some forms have annotations. Annotations are additional information on a form intended to provide on-screen instruction to users. Annotations have dark text on a colored background. Individual users can toggle annotations on and off.

## Templates
Templates simplify the process of submitting new records by populating fields automatically.
https://docs.servicenow.com/bundle/rome-platform-administration/page/administer/form-administration/concept/c_Templates.html

## Branding
Customize the look of your workspace with your company's logo and up to two brand colors.
- Open the workspace that you want to brand.
To brand a workspace that's already open, open the Settings menu by clicking your profile picture and selecting Configure workspace.
- Navigate to Work Experience > Administration > All Workspaces and click a workspace.
On the Workspace form, enter hex values using the format #FFFFFF as color values for Brand color 1 and Brand color 2.
Brand color 1 specifies the color of the branding bar above the Workspace. Brand color 2 appears in the heading of the Settings menu and in the left, side pane that contains the icons for home (home icon) and list (list icon). Workspace automatically applies different intensities of the colors in different places.
- Upload an image for your custom logo by clicking Click to add next to Custom Logo.
The image can be no larger than 120 kb. It displays 24 pixels high with a maximum width of 400 pixels. Supported file types include .jpg, .png, .bmp, .gif, .jpeg, .ico, and .svg.

https://docs.servicenow.com/bundle/rome-servicenow-platform/page/administer/workspace/task/brand-your-workspace.html
