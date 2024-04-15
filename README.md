**Project Title: Camera Monitoring Data Management**

**Description:**
This project aims to manage video and image data generated from camera monitoring systems. The script provided automates the process of copying the latest footage from specified camera angles to a designated folder for storage, while also maintaining a limit on the number of stored folders to prevent excessive storage usage.

**Scripts:**
- **Old Script:** Initially, the script utilized a dictionary (`fix_data`) to map company names to camera names. However, this functionality was not fully implemented.
- **Updated Script:** The updated script removes the unused dictionary and simplifies the logic for traversing directories. It also enhances clarity and maintainsability by introducing explicit checks for directory existence.

**Usage:**
1. Modify `main_folder` and `saving_folder` variables to match the directory paths on your system.
2. Run the script to execute the data management process.

**Instructions:**
1. Ensure Python is installed on your system.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the script using the command `python script_name.py`.
5. Monitor the terminal for progress updates and any error messages.

**GitHub Repository:**
- Repository Link: [Camera Monitoring Data Management](https://github.com/your_username/repository_name)
- Clone the repository to your local machine using the command:
  ```
  git clone https://github.com/your_username/repository_name.git
  ```

**Contributing:**
- Contributions to improve the script's functionality, efficiency, or documentation are welcome.
- Fork the repository, make your changes, and submit a pull request.
- For major changes, please open an issue to discuss the proposed modifications.

**License:**
- This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
- See the `LICENSE` file in the repository for more details.

Feel free to customize the README file further to include additional information or instructions specific to your project's requirements.
