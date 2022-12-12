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

All contents of this readme are subject to change. Please review the readme at Github to verify you have the latest Readme.

## Instructions
### How to Edit the Database
1) Download the database.db.sql from the main branch
2) Using your favorite SQL program, import the SQL file (or edit it directly if you like that)
3) Edit entries in the database. If you need to add a monster that is not included at all, any programs' "insert new record" should place it firmly at the bottom with the "latest" index and id number.
4) When done, save your changes and export the database as a SQL file.

### How to submit to the Monster Improvement Program
1) Upload the updated SQL file to a separate branch or a fork.
2) Create a PR on the github located at https://github.com/DexeeXI/XI-InfoBar-MIP and link the PR to the branch or fork the purposes of submission.

### How to use/test an updated monster SQL file
note: There may be periods where neither myself nor anyone else is going to post an "up to date" database.db file for a quick download and use. This is how one sets up and uses an SQL file.
1) Download a copy of the latest database.db.sql
2) Using your favorite SQL program, import the SQL file.
3) Save the resulting database as "database.db"
4) Navigate to your Windower/addons/Infobar folder. Create a backup of database.db located within.
5) Copy/move the database.db file generated to your Windower/Addons/Infobar folder and overwrite the database.db file within.
6) If FFXI is already running, all you should need to do is (re)target a foe. Changes will be visible immediately as the LUA script for Infobar does not require a reload for a change in the database. If things do not appear correctly, issue a //lua r Infobar to ensure the script is working correctly.
7) If any bugs are noticed with the display of information, let us know so we can double check and make sure it is our problem and not Infobar's

## Credits

Iryoku for creating the original Infobar Plugin for Windower

Iyouboushi for previous contributions to the Infobar Monster Database (https://iyouffxi.wordpress.com/category/programs/infobar/)

KenshiDRK for the Infobar Addon (https://github.com/KenshiDRK)

The entire Windower Team and all who've made it possible for FFXI to run on modern OSes with few problems! (https://www.windower.net/)

And all contributors not mentioned because I don't know all the names.
