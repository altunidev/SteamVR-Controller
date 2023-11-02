Links and research I'll need to sort out later

- SteamVR interfacing
    - https://store.steampowered.com/news/app/250820/view/2898585530113864598
    - https://github.com/ValveSoftware/openvr/wiki/SteamVR-Input
- https://hackaday.com/2021/12/16/a-hackers-journey-in-developing-a-new-vr-controller/
- https://skarredghost.com/2022/12/16/project-modular-open-vr-controllers-2/ (credit camacazzi)
- https://github.com/ashtuchkin/vive-diy-position-sensor (credit Lynx)
- https://github.com/matzman666/OpenVR-InputEmulator (credit JustinXenyx)
    - https://github.com/Louka3000/OpenVR-InputEmulator-Fixed (credit -Beige)
- HTC Vive Tracker 3.0 Pogo Pin Interfacing
    - https://developer.vive.com/us/hardware/tracker3/ (official HTC page, doesn't give all that many resources unfortunately)
    - Various forum posts
        - https://forum.htc.com/topic/8133-getting-started-with-the-htc-vive-tracker-pose-input-via-pogo-pins-in-unreal-engine-424/
        - https://forum.htc.com/topic/2589-vive-tracker-pogo-pin-hardware/
            - https://www.thingiverse.com/thing:2127180
            - https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/1946-0-00-15-00-00-03-0/5176096
        - https://forum.htc.com/topic/1131-vive-tracker-pogo-pins/
            - https://dl.vive.com/Tracker/Guideline/HTC_Vive_Tracker_Developer_Guidelines_v1.5.pdf ([local copy](assets/HTC_Vive_Tracker_Developer_Guidelines_v1.5.pdf))
                - 2017 Documentation
            - https://dl.vive.com/Tracker/Guideline/HTC_Vive_Tracker_Developer_Guidelines_v1.6.pdf ([local copy](assets/HTC_Vive_Tracker_Developer_Guidelines_v1.6.pdf))
                - Updated for 2018 design -- using Vive Tracker 2.0 design. Found essentially by replacing the guide version number in the URL. Downloaded PDF's for the purpose of archiving documentation (if there is an issue with this, please reach out). I believe the Vive Tracker 3.0 mainly had alterations to the form factor (to be smaller) and battery (to be longer), however much of the functionality remains the same.
    - The above few bullet points ultimately, some digging led me to this: https://developer.vive.com/resources/hardware-guides/vive-tracker-developer-guidelines/
        - Which lead me to the appropriate documentation for the Vive Tracker 3.0: https://developer.vive.com/documents/850/HTC_Vive_Tracker_3.0_Developer_Guidelines_v1.1_06022021.pdf
            - which now I have a [local copy here](assets/HTC_Vive_Tracker_3.0_Developer_Guidelines_v1.1_06022021.pdf).

- Various documentation bookmarks
    - SteamVR / OpenVR documentation and wiki stuff
        - https://developer.valvesoftware.com/wiki/SteamVR
        - https://github.com/ValveSoftware/openvr/wiki/API-Documentation
    - Tundra-Labs code (good starting point for Tundra Tracker Dev Board and TL448K6D)
        - https://github.com/tundra-labs/rp2040_examples
        - https://github.com/tundra-labs/TL448K6D24R-start | looking through the code, it seems rather empty unfortunately
        - https://github.com/tundra-labs (there might be more useful stuff that I missed initially)

- Existing designs
    - https://old.reddit.com/r/beatsaber/comments/bn6e4u/ragesaqs_school_of_making_a_vive_tracker_maul/ (credit ragesaq)