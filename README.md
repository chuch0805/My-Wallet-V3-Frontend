#### Google Script Macro steps
1. Create new spreadsheet on Google Sheet

    ````
     (https://groups.google.com/forum/#!forum/cornerstone-platform)
    ````
    
2. Import CSV file which you are going to add lat/long columns

    ````
    File menu / Import / Upload / Select a file from your computer 
    ````

    On `Import file` popup page:

        Import location - Select `Replace current sheet`
        
        Separator type - Select `Detect automatically`

        Convert text to numbers and dates - Select `No`

3. Create Script and Run
    
    Create

    ````
    Tools menu / Script editor / Import code from `geo_script.gs` file / Edit project name(for example: Geocode)
    ````

    Run

    ````
    Run menu / Run function / getGeocodingRegion / Review Permissions
    ````

    After script runs, `Geocode` will be created in menu.

4. Add/Fill columns for `Latitude` and `Longitude`

    Add new two columns for lat/long next to Zip column.

    Drag from the address to the newly created longitude column.

    Then:

    ````
    Geocode menu / Geocode Selected Cells(Address to Latitude, longitude)
    ````
