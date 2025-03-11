# Algorithm-for-File-Updates-in-Python
This project automates the removal of unauthorized IP addresses from an allow list based on a remove list. The algorithm ensures that only approved IPs remain in allow_list.txt.

**Process**

- Open & Read File – Load allow_list.txt into a string.
- Convert to List – Transform the string into a list of IP addresses.
- Iterate & Remove – Check each IP in the remove_list and remove matches.
- Update File – Convert the list back to a string and overwrite allow_list.txt.

**Key Methods Used**
- .read() – Reads file contents.
- .split() – Converts a string into a list.
- .remove() – Deletes matching IP addresses.
- .join() – Converts a list back to a string.
- .write() – Updates the file with revised data.

