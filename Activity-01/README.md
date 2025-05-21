Which enhancement you chose
I chose the `--min-size` filter enhancement.  
This option allows the script to show only `.txt` files that are larger than a specified file size (in kilobytes).

How to run your script
python3 setup_files.py
python3 scan.py test_root


Sample output
itakato@Takatos-MacBook-Air-4 Activity-01 % python3 scan.py test_root
Scanning: /Users/itakato/Documents/IT390R/Github/activities-itakato/Activity-01/test_root
Found 20 text files:

File                                      Size (KB)
----------------------------------------------------
docs/file2.txt                                  0.1
docs/file3.txt                                  0.1
docs/file1.txt                                  0.1
docs/file0.txt                                  0.1
docs/file4.txt                                  0.1
logs/file2.txt                                  0.1
logs/file3.txt                                  0.1
logs/file1.txt                                  0.1
logs/file0.txt                                  0.1
logs/file4.txt                                  0.1
docs/subfolder/file2.txt                        0.1
docs/subfolder/file3.txt                        0.1
docs/subfolder/file1.txt                        0.1
docs/subfolder/file0.txt                        0.1
docs/subfolder/file4.txt                        0.1
logs/archive/file2.txt                          0.1
logs/archive/file3.txt                          0.1
logs/archive/file1.txt                          0.1
logs/archive/file0.txt                          0.1
logs/archive/file4.txt                          0.1
----------------------------------------------------
Total size: 2.0 KB