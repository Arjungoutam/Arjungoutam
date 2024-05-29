#!/usr/bin/python
# -*- coding: UTF-8 -*-

from os import system, name
import itertools
import threading
import time
import sys
import datetime
from base64 import b64decode, b64encode
from datetime import date

expirydate = datetime.date(2025, 8, 30)  # Update expiry date
today = date.today()

def hero():
    def chalo():
        done = False

        def animate():
            for c in itertools.cycle(['|', '/', '-', '\\']):
                if done:
                    break
                sys.stdout.write('\rconnecting to the 55club01.com server for next colour--------- ' + c)
                sys.stdout.flush()
                time.sleep(0.1)
            sys.stdout.write('\rDone!     ')

        t = threading.Thread(target=animate)
        t.start()
        time.sleep(10)
        done = True

    def chalo1():
        done = False

        def animate():
            for c in itertools.cycle(['|', '/', '-', '\\']):
                if done:
                    break
                sys.stdout.write('\rgetting the colour wait --------- ' + c)
                sys.stdout.flush()
                time.sleep(0.1)
            sys.stdout.write('\rDone!     ')

        t = threading.Thread(target=animate)
        t.start()
        time.sleep(10)
        done = True

    def clear():
        if name == 'nt':
            _ = system('cls')
        else:
            _ = system('clear')

    clear()
    y = 1
    newperiod = period
    banner = '55club01.com'
    thisway = [2, 6, 8, 11, 12, 15, 16, 18, 19, 20]
    thatway = [1, 3, 4, 5, 7, 9, 10, 14, 13, 17]
    numbers = []
    i = 1
    while y:
        clear()
        system(banner)
        print("Contact me on Mobile No.7389117291")
        print("Enter ", newperiod, " Parity Price :")
        current = int(input())
        chalo()
        print("\n---------Successfully Connected to the server-----------")
        chalo1()
        print("\n---------Successfully got the colour -------------")
        print('\n')

        def getSum(n):
            return sum(int(digit) for digit in str(n))

        if i in thisway:
            m = getSum(current)
            n = current % 40
            if (m % 2 == 0 and n % 2 == 0) or (m % 2 == 1 and n % 2 == 1):
                if current in numbers:
                    print(newperiod + 1, " : Red 🔴")
                else:
                    print(newperiod + 1, " : Green 🟢")
            else:
                if current in numbers:
                    print(newperiod + 1, " : Green 🟢")
                else:
                    print(newperiod + 1, " : Red 🔴")
        if i in thatway:
            m = getSum(current) + 1
            n = current % 40
            if (m % 2 == 0 and n % 2 == 0) or (m % 2 == 1 and n % 2 == 1):
                if current in numbers:
                    print(newperiod + 1, ": Green 🟢")
                else:
                    print(newperiod + 1, ": Red 🔴")
            else:
                if current in numbers:
                    print(newperiod + 1, ": Red 🔴")
                else:
                    print(newperiod + 1, ": Green 🟢")

        i += 1
        newperiod += 1
        numbers.append(current)
        y = input("Do you want to play : Press 1 and 0 to exit \n")
        if y == '0':
            y = False
        if len(numbers) > 11:
            clear()
            system('figlet Thank you!!')
            print("Play on next specified time!!")
            print("-----------Current Time UP----------")
            sys.exit(" \n \n \n Contact on Telegram @tusharma3")
            print(numbers)

if expirydate > today:
    now = datetime.datetime.now()
    First = now.replace(hour=10, minute=55, second=0, microsecond=0)
    Firstend = now.replace(hour=11, minute=35, second=0, microsecond=0)
    Second = now.replace(hour=13, minute=55, second=0, microsecond=0)
    Secondend = now.replace(hour=14, minute=40, second=0, microsecond=0)
    Third = now.replace(hour=17, minute=55, second=0, microsecond=0)
    Thirdend = now.replace(hour=18, minute=35, second=0, microsecond=0)
    Final = now.replace(hour=19, minute=55, second=0, microsecond=0)
    Finalend = now.replace(hour=20, minute=35, second=0, microsecond=0)

    if First < now < Firstend:
        period = 220
        hero()
    elif Second < now < Secondend:
        period = 873
        hero()
    elif Third < now < Thirdend:
        period = 360
        hero()
    elif Final < now < Finalend:
        period = 400
        hero()
    else:
        period = 899
        hero()
else:
    def clear():
        if name == 'nt':
            _ = system('cls')
        else:
            _ = system('clear')

    code = "MZXCD"
    code1 = "BSDF3"
    code2 = "ASA6"
    test = "SD3"
    night = "N13"
    nextday = "DSDSXS"
    banner = '55club01.com'
    rava = 0
    now = datetime.datetime.now()
    Second = now.replace(hour=0, minute=55, second=0, microsecond=0)
    Secondend = now.replace(hour=23, minute=55, second=0, microsecond=0)
    Third = now.replace(hour=15, minute=30, second=0, microsecond=0)
    Thirdend = now.replace(hour=18, minute=34, second=0, microsecond=0)
    Final = now.replace(hour=18, minute=25, second=0, microsecond=0)
    Finalend = now.replace(hour=22, minute=35, second=0, microsecond=0)

    if Second < now < Secondend:
        rava = 404
    elif Third < now < Thirdend:
        rava = 350
    elif Final < now < Finalend:
        rava = 410

    system(banner)
    print("*--------*--------*--------*----*")
    print("Your hack has expired--- please contact")
    print(" on telegram ----@tusharma3 for activation")
    print("     plan amount --    total limit ")
    print(" 1.  2000 INR ------   1 Day 500 Games")
    print(" 2.  3000 INR ------   2 Days 1000 Games")
    print(" 3.  5000 INR ------   7 Days 2100 Games")
    print("*---------*--------*-------------*--")
    print("Beware of fraudsters!!!")

    while True:
        print("My banking name is vusha")
        print("After you pay to our UPI ID")
        print("Activate Hack by entering the correct")
        print("(UTR) or UPI reference number")
        print("To Activate the hack ")
        print("if it Doesn't open contact Me on telegram")
        print("*--------*--------*--------")
        print("*---------*--------*--------")
        print("payhere--- UPI :")
        print("UPI :supper911@ibl")
        print(" if you have already paid to the above UPI")
        print("Enter Your activation code")

        arjun = input(": ")

        if arjun in [code, code1, code2, test, night, nextday]:
            clear()
            print("Activation successful.")
            break
        else:
            print("Invalid activation code. Try again.")
     ![Screenshot_2024-05-26-02-12-19-207_com instagram android](https://github.com/Arjungoutam/Arjungoutam/assets/171119066/575f26b8-f179-4abc-ba91-e99db225e501)
       
