

# EmptyOS Original Beta build

* EmptyOS is a lightweight, closed-source Hobby OS developed for the X86 architecture.
* Published and developed by Twoo! Studio (2o! Studio)

<img width="1372" height="943" alt="IMG_3684" src="https://github.com/user-attachments/assets/d98ba5f5-ec34-4eb7-b3df-3cf27faf1d23" />

<img width="2208" height="1242" alt="IMG_4097" src="https://github.com/user-attachments/assets/5b9308b6-f276-4644-90c0-8fd24cf3047f" />

### Required configuration
```txt
- X86
- RAM <1MB
- Storage 6MB
```

### Orther

##### code of the "ver" command =]]
```C
void ver() {
    print("                       ORIGINAL\n", GREEN);
    print(" version b0.4.2.37\n", RED);
    print(" x86 Edition\n", GREEN);
        if (version == 1) {print("NOTE: THIS IS A BETA VERSION\n\n", YELLOW);}
	     else if (version == 0) {print("Stable version\n\n", GREEN);}
	     else print("Not verified.\n\n", RED);
         
        if (isdev == 1) {print("DEV mode", CYAN);}
            else print(" ", RED);
    print(" Youtube @B40Ph4m\n", GREEN);
    print(" (c) Twoo! Studio 2026\n", YELLOW);
}
```

### Work progress (empty)

### Changelog



