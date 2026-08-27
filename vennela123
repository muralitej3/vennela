# 1
import os

# 2
import platform

# 3
import datetime

# 4
print("===== DEVOPS SYSTEM MONITOR =====")

# 5
hostname = platform.node()

# 6
system = platform.system()

# 7
release = platform.release()

# 8
machine = platform.machine()

# 9
print("Hostname:", hostname)

# 10
print("Operating System:", system)

# 11
print("OS Release:", release)

# 12
print("Machine:", machine)

# 13
current_time = datetime.datetime.now()

# 14
print("Current Time:", current_time)

# 15
print("-------------------------------")

# 16
def check_directory(path):

# 17
    if os.path.exists(path):

# 18
        print(path, "exists")

# 19
    else:

# 20
        print(path, "does not exist")

# 21
check_directory("/tmp")

# 22
check_directory("/etc")

# 23
check_directory("/var")

# 24
check_directory("/home")

# 25
print("-------------------------------")

# 26
def list_files(path):

# 27
    try:

# 28
        files = os.listdir(path)

# 29
        print("Files in", path)

# 30
        for file in files:

# 31
            print(file)

# 32
    except PermissionError:

# 33
        print("Permission denied")

# 34
    except FileNotFoundError:

# 35
        print("Directory not found")

# 36
list_files("/tmp")

# 37
print("-------------------------------")

# 38
def create_log():

# 39
    filename = "devops.log"

# 40
    file = open(filename, "w")

# 41
    file.write("DevOps monitoring started\n")

# 42
    file.write("Server check completed\n")

# 43
    file.write("Application status: UP\n")

# 44
    file.close()

# 45
    print("Log file created:", filename)

# 46
create_log()

# 47
print("-------------------------------")

# 48
def read_log():

# 49
    filename = "devops.log"

# 50
    if os.path.exists(filename):

# 51
        file = open(filename, "r")

# 52
        data = file.read()

# 53
        print("LOG DATA:")

# 54
        print(data)

# 55
        file.close()

# 56
    else:

# 57
        print("Log file not found")

# 58
read_log()

# 59
print("-------------------------------")

# 60
servers = ["server01", "server02", "server03"]

# 61
print("Server List:")

# 62
for server in servers:

# 63
    print(server)

# 64
print("-------------------------------")

# 65
status = {

# 66
    "server01": "UP",

# 67
    "server02": "UP",

# 68
    "server03": "DOWN"

# 69
}

# 70
for server, state in status.items():

# 71
    print(server, ":", state)

# 72
print("-------------------------------")

# 73
for server, state in status.items():

# 74
    if state == "UP":

# 75
        print(server, "is healthy")

# 76
    else:

# 77
        print(server, "requires attention")

# 78
print("-------------------------------")

# 79
tools = ["Git", "Jenkins", "Docker", "AWS", "Kubernetes"]

# 80
print("DevOps Tools:")

# 81
for tool in tools:

# 82
    print("-", tool)

# 83
print("-------------------------------")

# 84
def deployment_status(application):

# 85
    print("Checking deployment:", application)

# 86
    return "SUCCESS"

# 87
result = deployment_status("Payment-App")

# 88
print("Deployment Result:", result)

# 89
print("-------------------------------")

# 90
if result == "SUCCESS":

# 91
    print("Deployment completed successfully")

# 92
else:

# 93
    print("Deployment failed")

# 94
print("-------------------------------")

# 95
print("Monitoring completed")

# 96
print("Server:", hostname)

# 97
print("Status: HEALTHY")

# 98
print("Environment: Production")

# 99
print("Alert Status: No alerts")

# 100
print("===== END MONITORING =====")
