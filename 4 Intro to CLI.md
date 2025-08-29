CLI = Command Line Interface
Connect using Console Port
    Rollover Cable
        1->8
        2->7
        3->6
        4->5
        5->4
        6->3
        7->2
        8->1
        RJ45 or USB-Mini B

PuTTy is a good console emulator
    Settings
        Speed: 9600bps
        Data bits: 8
        Stop bits: 1
        Parity: None
        Flow control: None


User EXEC Mode
Hostname>
    Read-only mode, sorta

    Command "enable" to enter Privileged EXEC Mode

Privileged EXEC Mode
Hostname#
    File write privileges
    conf t to elevate to GCM


Global Configuration Mode
Hostname(config)#
    "run [privileged-exec-level-command]"

running-config/startup-config
    running = current, active config
    startup = loaded upon restarting device
        "show running-config" 
        "show startup-config"

    Save Configuration    
        "write"
        "write memory"
        "copy running-config startup-config"

    Security (lol)
        "enable password ______"
        "service password-encryption"
            encrypts display of pw in config 
        "enable secret _______"
            configures md5 encrypted pw

    Removing Commands from Configuration
        type "no" before a Command
    