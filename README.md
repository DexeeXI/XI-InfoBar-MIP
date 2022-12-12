Copyright © 2022, Dexee
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer in the
      documentation and/or other materials provided with the distribution.
    * Neither the name of XI InfoBar Database Monster Improvement Program nor the
      names of its contributors may be used to endorse or promote products
      derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL DEXEE BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

# XI-InfoBar-MIP
Infobar Monster Improvement Program
Welcome to what will hopefully be a long term home for the InfoBar Database Monster Improvement Program for Final Fantasy XI.

The purpose behind this program is to provide for long term support for the database that is used as part of InfoBar.

## History

InfoBar was originally programmed and created as a plugin many years ago, of which it had become abandoned some time around 2012 or so. The idea behind InfoBar was to give the user information of what a target monster in the game has, things such as their expected level range, resistances, immunities, drops, and more. This led to the plugin still being used for many years, despite that neither the plugin nor the database was being maintained. The source code, to the best of my knowledge, had never been released by the original author.

After some time had passed, KenshiDRK created a LUA-based version of the same InfoBar plugin, allowing for InfoBar to live on in a new format. However, the database was still lacking some entries. Kenshi had done an amazing job of adding in some of the monsters and content that had been implemented since the last major revision of the database. Despite it all, there are still a variety of monsters that have either been added due to new content over the years, adjustments made to existing monsters and much more that have gone unnoticed.

## Today and onward

It brings us to today. I started the initiative, even with my very limited time in FFXI (even after attempting to give XI a go almost 20 years ago now!), because I do appreciate the work of having data available to one self. While throwing yourself head first into a situation can help with the learning experience, sometimes having a quick snippet of information made available to you can the difference in making an informed decision before you go head-first into the jaws of death.

I do not know what KenshiDRK's plans are regarding ongoing development or maintenance of the Windower 4 variety of InfoBar as a LUA addon. I also do not know if there is any intention to bring InfoBar over to Windower 5. But what I do know is that there are others like myself that still use InfoBar today and want to make a change in a good direction.

## Current

We need to figure out what fields in the database we want to keep. Most of it is perfectly fine and doesn't need to change much. But a few extra fields that aren't utilized probably need to go.

We need to figure out if we want JSON or .SQL for assisting with visible tracking, since binaries can't exactly be compared side to side.

Once we've got the groundwork setup, we can move forward with the daunting task of updating/adding monster info. Time consuming, but a work that will be noticed by users and appreciated for, none the less.

Migrated to separate repo to do more proper work and not worry about accidentally PRing into Windower with an incomplete product.
