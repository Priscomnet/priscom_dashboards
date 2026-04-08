import time
import random
import csv

with open('data.csv', mode='w',newline='') as file:
    writer = csv.writer(file)
    writer.writerow(["time", "value"])

    for i in range(50):
        value = random.randint(20, 30)
        writer.writerow([i, value])
        time.sleep(1)