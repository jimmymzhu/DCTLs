# Arri LogC4 ACES IDT
Adding the Arri LogC4 ACES IDT file to Davinci Resolve:

----------------------------------------
- Navigate to the "ACES Transforms" folder in Resolve's main application support folder.
    - MacOS: "~/Library/Application Support/Blackmagic Design/DaVinci Resolve/ACES Transforms"   double check folders again
    - Windows: "%AppData%\Blackmagic Design\\DaVinci Resolve\\Support\\ACES Transforms"
    - Linux: "~/.local/share/DaVinciResolve/ACES Transforms"
- Place Arri_LogC4.dctl in the IDT subfolder.
- Start Resolve.

At start up, Resolve loads all the ACES DCTLs inside the "ACES Transforms/IDT" and "ACES Transforms/ODT" folders.