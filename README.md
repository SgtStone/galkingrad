galkingrad
==========

Urban settlement in Devil's Castle. Only works in DayZ Epoch

==========
INSTALLATION
==========

Step 1: insert the attached Schultz_Galkingrad.sqf in your server.pbo in the "Maps" dir

Step 2: add the following code at the bottom of Server.pbo/init/server_fuctions.sqf

    execVM "\z\addons\dayz_server\Maps\Schultz_Galkingrad.sqf";

Step 3 (optional): edit your custom markers config file to add Galkingrad's marker:

    _devils  = createMarker ["_devils", [6884.2231, 11438.902]];
    _devils  setMarkerText "Galkingrad";
    _devils  setMarkerType "Faction_CDF";
    _devils  = _devils ;
  
Step 4: Enjoy but give credits to EpochRP.com
