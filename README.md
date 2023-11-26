
# ADT Collection

*Various iDevice ADT dumps.*

<br>
<br>

## How To Dump

<br>

-   Download **[PongoOS]**

    ```sh
    git clone https://github.com/checkra1n/PongoOS
    cd PongoOS
    ```

    <br>

-   Follow the instruction of PongoOS  
    by setting it up using `checkra1n`.

    <br>

-   Generate the dump with:

    ```sh
    python3 scripts/issue_cmd.py dt
    python3 scripts/fetch_stdout.py > Dump.adt
    ```

    <br>

-   Censor your  `IMEI`  ,  `MAC`  ,  `SERIAL`  and  
    `NVRAM`  as well as other unique identifiers.
    
    <br>
    
-   Add a file with the following format into your  
    local copy of this repository and copy over  
    the dumped and censored information.

    ```
    adt_collection/Devices/< SocName >/< Device Name >.adt
    ```
    
    <br>
    
-   Open a new pull request with your changes.

<br>


<!----------------------------------------------------------------------------->

[PongoOS]: https://github.com/checkra1n/PongoOS
