# macdaddy
mac address scrambler 

Run as bash script or as a single line:

python3 -c "import os; import random; x = [os.system('macchanger -r $interface') for x in range(50, random.randint(60, 350))]"
