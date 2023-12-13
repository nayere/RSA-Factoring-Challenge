
#!/usr/bin/python3

# library to get arguments
import sys


# fn unpack number factorial
def fc():
    """
    This function reads a file provided as a command-line argument (sys.argv[1]).
    It iterates through each line in the file.
    Converts each line to an integer (revnumber = int(revnumber)).
    Checks if the number is even and factors it by 2 if it is.
    if the number is odd, it starts checking for factors from 3 up to half the number (revnumber // 2). 
    It factors the number and prints it in the format n=p*q (where p and q are factors of n).
    """
    try:
      """Exception Handling (try-except): The try block attempts to read the file specified in the command-line argument and perform the factorization process."""
        revfile = sys.argv[1]
        with open(revfile) as f:
            for revnumber in f:
                revnumber = int(revnumber)
                if revnumber % 2 == 0:
                        print("{}={}*{}".format(revnumber, revnumber // 2, 2))
                        continue
                i = 3
                while i < revnumber // 2:
                    if revnumber % i == 0:
                        print("{}={}*{}".format(revnumber, revnumber // i, i))
                        break
                    i = i + 2
                if i == (revnumber // 2) + 1:
                    print("{}={}*{}".format(revnumber, revnumber, 1))
    except (IndexError):
        pass


# autostart 
# Autostart (fc()): At the end of the script, the function fc is invoked, triggering the file reading and factorization process.
fc()
