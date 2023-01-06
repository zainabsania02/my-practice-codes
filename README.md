# my-practice-codes
# first code - traffic lights 
import time 
def traffic_signal():
    while True:
        print("Red")
        time.sleep(5)
        print("Yellow")
        time.sleep(2)
        print("Green")
        time.sleep(7)
        break
traffic_signal()

# while True is used to run the loop forever ,but to stop it i have tried using break in it 
