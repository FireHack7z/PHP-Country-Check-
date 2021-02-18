# PHP Country Check
Check a country  where name / iso3166 and more

  ______ _          _    _            _    ______   
 |  ____(_)        | |  | |          | |  |____  |  
 | |__   _ _ __ ___| |__| | __ _  ___| | __   / /___
 |  __| | | '__/ _ \  __  |/ _` |/ __| |/ /  / /_  /
 | |    | | | |  __/ |  | | (_| | (__|   <  / / / / 
 |_|    |_|_|  \___|_|  |_|\__,_|\___|_|\_\/_/ /___|
                                                    
                                                    


Power By FireHack7z
Channel   : https://www.youtube.com/channel/UCBu53oQEkGGGXXPdQ-09wyQ
Twitter   : https://twitter.com/firehack7z
Instagram : https://www.instagram.com/firehack7z/?hl=fr

THANK YOU FOR SUPPORT <3

Usage :

<?php 

    //Load
      require_once "./list.function.php";
      require_once "./check.function.php";
    //Avaible Data : 
    //"name";
    //"alpha-2";
    //"alpha-3";
    //"country-code";
    //"iso_3166-2";
    //"region";
    // "sub-region";
    //"intermediate-region";
    //"region-code";
    //"sub-region-code";
    //"intermediate-region-code";     
    
    //replace $data where avaible data
    //check if exist with $arg (exemple : FRA / USA...)
    
    //Function :
      CountryCheck($arg,$data);
    //Exemple : 
      if(CountryCheck("FRA","alpha-3")){
        echo "ok";
      }
      
     //False Exemple : 
           if(CountryCheck("RANDOM","alpha-3")){
             echo "ok";
           }else{
            echo "error";
           }
  //LISTING
    //Function : CountryList();
    //Exemple : var_dump(CountryList());
    //Exemple 2 : var_dump(CountryList())['name'];
    
    
?>
