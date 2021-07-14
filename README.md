# ProffieProfiles
Custom Saber Profiles for ProffieOS

## Usage
Paste the profiles into your lightsaber's config file, in one of the profile items, as such:
```
Preset presets[] = {
// previous presets go here...
{"Font", "pathto/music.wav", 
// StylePtr<...> CODE from one of these text files GOES HERE*
, "Stylename"},
// more presets go here...
};
```  

\* Note that if you have multiple "blades" (blades and/or accent LEDs), you order each blade style, such as the `StylePtr<...>` obtained from the text files, and any other blade styles for those "blades", in the amount and order defined in the `BladeConfig[] blades` section in your config.

## Special Thanks
Thank you very much to Fett263 for the amazing style library that helped me learn and develop these styles and many more to come. Of course, a big thank you to Fredrik, and all of the contributors to ProffieOS, for an amazing system that turns a fancy glowstick into a piece of technology amazing beyond words. 

## License information
ProffieOS (Copyright (c) 2016-2019 Fredrik Hubinette) is licensed under the GNU General Public License v3.0. You can find the latest information at https://github.com/profezzorn/ProffieOS.  

Some style code used was created or otherwise provided by Fett263, and is available on his website at https://fett263.s3.us-east-2.amazonaws.com/index.html. Please see this site for more information.  
Styles created by Fett263 designed for ProffieOS: Copyright (c) 2018-2021 Fernando da Rosa
