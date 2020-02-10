**VAC warning:** This clantagTool is technically a hack. Joining VAC protected servers will probably get you VAC banned.
# Building from Source
* Clone this repositorie in Visual Studio, Dont forget check your Windows SDK version and Platform Toolset setting.
* Then have fun.

## If CSGO update, how to fix this tool.
* You only need to fix the `#define CLANTAGADR 0xXXXXX` in [ClantagChanger.cpp](/ClantagChanger.cpp).
* You can find this value [here](https://github.com/frk1/hazedumper/blob/master/csgo.hpp), its named `dwSetClanTag`.
