Technologies Used:

    UI: HTML, Javascript, AJAX, JQuery

    Business Logic: Java with machine learning algorithms, spring boot, gradle, hibernate

    Backend: MySQL database


Algorithm Implemented:

    K-Nearest Neighbours

Steps to Run the code:

    The project consists of three repositories(files):
    RS_Parser - Contains source code for parsing the dblp.xml and saving in database.
        In RS_Parser, there will be an sh file named “setup.sh”. Run this with the following way:
            sh setup.sh <path-to-dblp-xml-file>
    DBLP_Recommender - contains the Spring server source code.
        Go to DBLP_Recommender and the run the following command to start the server:
            ./gradlew build && java -jar build/libs/dblp-0.1.0.jar
    index.html - This is the UI for the project.
        Open this html in any browser of your choice.


Assumptions Made:
    There are 22 attributes, but we considered only 7 as per the requirement for the recommender System:
