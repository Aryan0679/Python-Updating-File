

## Scenario

You are a security professional working at a health care company. As part of your job, you're required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees you must remove from this allow list.

Your task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, you should remove those IP addresses from the file containing the allow list.

## How It Works

- The script reads the current allow list from a text file.
- It compares each IP address against a predefined remove list.
- Any matching IP addresses are removed from the list.
- The cleaned list is then written back to the file, replacing the old one.
- Finally, it prints the updated allow list to the console for verification.

## Skills

- **Python Scripting for Access Control Automation**  
  Automating the cleanup of allowlists based on dynamic IP restrictions.

- **File Handling and Data Parsing**  
  Reading, modifying, and rewriting structured access control data using Python.

- **Logical Filtering and Conditional Logic**  
  Identifying and removing unauthorized entries through list comparison and filtering.
