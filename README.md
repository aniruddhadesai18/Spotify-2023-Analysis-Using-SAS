# Spotify-2023-Analysis-Using-SAS

This project analyzes the Spotify 2023 dataset to uncover trends in music streaming. It highlights the top streamed tracks and artists, compares the performance of solo versus collaborative tracks, and examines monthly release patterns. By exploring these insights, the project aims to provide a better understanding of listener preferences and the dynamics of the music industry.

Here’s a structured outline for your README file on GitHub, detailing the steps for using your project:

Steps to Run the Project

Step 1: Download the Raw Data File
- Download the raw Spotify 2023 dataset (spotify dataset-2023.csv) from the repository.

Step 2: Download the Program File
- Download the SAS program file (e.g., `program file.sas`) from the repository.

Step 3: Change the Library Path
- Open the SAS program file.
- Change the path in the **libname statement** to specify the directory where you want to save the datasets.

  libname mydata 'C:\path\to\your\directory';
  

Step 4: Update the Raw Data Import Path
- In the program file, locate the `PROC IMPORT` section for the raw data file.
- Change the path to match the location of the downloaded raw data file.


Step 5: Run the Program
- Execute the program in SAS to perform the analysis and generate the insights.

Step 6: View the Results
- Review the generated ODS report for insights on the top tracks, artists, and streaming trends.


*Note : 
  I have implemented a macro in SAS to efficiently search for songs by their name and artist in my Spotify project.
  you can change it as per your requirement.


If you encounter any issues or have questions regarding the project, please don't hesitate to reach out. You can contact me at aniruddhadesai18@gmail.com, and I'll be happy to assist you.  

  
