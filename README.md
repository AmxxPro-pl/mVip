# mVip


### Description
- Rozbudowany system VIP na serwery CS 1.6
- Uniwersalny na większość trybów gry

### Requirements
- AMXModX 1.9 / AMXModX 1.10

### Configuration
<details>
  <summary><b>mVip_Core.cfg</b></summary>

```
mVip_Flags "t"                                   // Flagi, które musi posiadać gracz, aby otrzymać VIP'a
mVip_FreeVip "1"                                 // Czy ma działać darmowy VIP w godzinach ( 1 - Tak | 0 - Nie )
mVip_FreeVip_Od "18"                             // Od ktorej godziny ma działać darmowy VIP ( 18 - Domyślnie )
mVip_FreeVip_Do "10"                             // Do ktorej godziny ma działać darmowy VIP ( 10 - Domyślnie )
mVip_FreeVip_Steam "1"                           // Czy ma działać darmowy VIP dla steam ( 1 - Tak | 0 - Nie )
mVip_Faq_Payments "1"                            // Czy ma wyswietlac FAQ dostępne platności ( 1 - Tak | 0 - Nie )
mVip_Faq_SklepCS "1"                             // Czy ma wyswietlac FAQ SklepCS ( 1 - Tak | 0 - Nie )
mVip_Extra_Jump "2"                              // Ile skokow ma posiadać ( 0 - Nic )
mVip_Max_Hp "100"                                // Maksymalna ilość HP ( 100 - Domyślnie )
mVip_Disable_Buy_Helmet_First_Round "1"          // Czy zablokować możliwośc kupna hełmu w 1 rundzie? ( 1 - Tak | 0 - Nie )
mVip_Enable_Kevlar "1"                           // Darmowy Kevlar ( 1 - Tak | 0 - Nie )
mVip_Kevlar_Amount "100"                         // Ilość Kevlara
mVip_Kevlar_Round "1"                            // Od której rundy ma dostawać
mVip_Enable_Helmet "1"                           // Darmowy Hełm ( 1 - Tak | 0 - Nie )
mVip_Helmet_Round "2"                            // Od której rundy ma dostawać
mVip_Enable_Shield "0"                           // Darmowy Tarcza ( 1 - Tak | 0 - Nie )
mVip_Shield_Round "2"                            // Od której rundy ma dostawać
mVip_Enable_Defuser "1"                          // Darmowy Defuser ( 1 - Tak | 0 - Nie )
mVip_Defuser_Round "1"                           // Od której rundy ma dostawać
mVip_Gravity_Amount "700"                        // Grawitacja gracza ( 700 - Domyślnie )
mVip_Gravity_Round "1"                           // Od której rundy ma dostawać
mVip_Speed_Amount "1.0"                          // Szybkość gracza ( 0 - Domyślnie )
mVip_Speed_Round "0"                             // Od której rundy ma dostawać
mVip_Extra_Hp_Spawn "0"                          // Dodatkowe HP przy spawnie ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Hp_Spawn_Round "1"                    // Od której rundy ma dostawać
mVip_Extra_Money_Spawn "0"                       // Dodatkowe $ przy spawnie ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Spawn_Round "1"                 // Od której rundy ma dostawać
mVip_Extra_Money_Spawn_Info "1"                  // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Kill "0"                        // Dodatkowe $ za zabójstwo ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Kill_Round "1"                  // Od której rundy ma dostawać
mVip_Extra_Money_Kill_Info "1"                   // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Kill_Hs "0"                     // Dodatkowe $ za Headshota ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Kill_Hs_Round "1"               // Od której rundy ma dostawać
mVip_Extra_Money_Kill_Hs_Info "1"                // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Assist "100"                    // Dodatkowe $ za asystę ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Assist_Round "1"                // Od której rundy ma dostawać
mVip_Extra_Money_Assist_Info "1"                 // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Revenge "200"                   // Dodatkowe $ za zemstę ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Revenge_Round "1"               // Od której rundy ma dostawać
mVip_Extra_Money_Revenge_Info "1"                // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Bomb_Picked "150"               // Dodatkowe $ za podniesienie bomby ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Bomb_Picked_Round "1"           // Od której rundy ma dostawać
mVip_Extra_Money_Bomb_Picked_Info "1"            // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Bomb_Dropped "200"              // Ile ma stracić $ za wyrzucenie bomby ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Bomb_Dropped_Round "1"          // Od której rundy ma dostawać
mVip_Extra_Money_Bomb_Dropped_Info "1"           // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Plant "150"                     // Dodatkowe $ za podłożenie bomby ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Plant_Round "1"                 // Od której rundy ma dostawać
mVip_Extra_Money_Plant_Info "1"                  // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Defuse "150"                    // Dodatkowe $ za rozbrojenie bomby ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Defuse_Round "1"                // Od której rundy ma dostawać
mVip_Extra_Money_Defuse_Info "1"                 // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Hostage_Rescued "150"           // Dodatkowe $ za uratowanie zakładnika ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Hostage_Rescued_Round "1"       // Od której rundy ma dostawać
mVip_Extra_Money_Hostage_Rescued_Info "1"        // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Hostage_Touched "50"            // Dodatkowe $ za próbę uratowanie zakładnika ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Hostage_Touched_Round "1"       // Od której rundy ma dostawać
mVip_Extra_Money_Hostage_Touched_Info "1"        // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Knife "0"                       // Dodatkowe $ za zabójstwo z noża ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Knife_Round "1"                 // Od której rundy ma dostawać
mVip_Extra_Money_Knife_Info "1"                  // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Money_Grenade "0"                     // Dodatkowe $ za zabójstwo z granatu ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Money_Grenade_Round "1"               // Od której rundy ma dostawać
mVip_Extra_Money_Grenade_Info "1"                // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Hp_Kill "0"                           // Dodatkowe HP za zabójstwo ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Hp_Kill_Round "1"                     // Od której rundy ma dostawać
mVip_Extra_Hp_Kill_Info "1"                      // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Hp_Kill_Hs "1"                        // Dodatkowe HP za Headshota ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Hp_Kill_Hs_Round "1"                  // Od której rundy ma dostawać
mVip_Extra_Hp_Kill_Hs_Info "1"                   // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Hp_Assist "0"                         // Dodatkowe HP za asystę ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Hp_Assist_Round "1"                   // Od której rundy ma dostawać
mVip_Extra_Hp_Assist_Info "1"                    // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Hp_Knife "0"                          // Dodatkowe HP za zabójstwo z noża ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Hp_Knife_Round "1"                    // Od której rundy ma dostawać
mVip_Extra_Hp_Knife_Info "1"                     // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Extra_Hp_Grenade "0"                        // Dodatkowe HP za zabójstwo z granatu ( 0 - Jeżeli ma nie dostawać )
mVip_Extra_Hp_Grenade_Round "1"                  // Od której rundy ma dostawać
mVip_Extra_Hp_Grenade_Info "1"                   // Powiadomienie na czat ( 1 - Tak | 0 - Nie )
mVip_Enable_Footsteps "0"                        // Ciche chodzenie ( 1 - Tak | 0 - Nie )
mVip_Footsteps_Round "1"                         // Od której rundy ma dostawać
mVip_Visibility_Amount "255"                     // Widzialność gracza ( 255 - Podstawowa )
mVip_Visibility_Round "1"                        // Od której rundy ma dostawać
mVip_Damage_Give_Percent "100"                   // Obrażenia zadawane przez gracza w % ( 100 - Normalne )
mVip_Damage_Give_Round "1"                       // Od której rundy ma dostawać
mVip_Enable_Damage_Take_Falling "0"              // Obrażenia przy upadku ( 1 - Tak | 0 - Nie )
mVip_Damage_Take_Falling_Round "1"               // Od której rundy ma dostawać
mVip_Enable_Welcome_Goodbye_Dhud "1"             // Przywitanie/Pożegnanie w dhud ( 1 - Tak | 0 - Nie )
mVip_Enable_Welcome_Goodbye_Chat "1"             // Przywitanie/Pożegnanie na czat ( 1 - Tak | 0 - Nie )
mVip_Enable_Full_Magazine "0"                    // Pełen magazynek za zabójstwo ( 1 - Tak | 0 - Nie )
mVip_Full_Magazine_Round "1"                     // Od której rundy ma dostawać
mVip_Enable_Primary_Weapon_Menu "1"              // Czy ma się wyświetlać menu z karabinami ( 1 - Tak | 0 - Nie )
mVip_Primary_Weapon_Menu_Round "4"               // Od której rundy ma dostawać
mVip_Enable_Secondary_Weapon_Menu "1"            // Czy ma się wyświetlać menu z pistoletami ( 1 - Tak | 0 - Nie )
mVip_Secondary_Weapon_Menu_Round "1"             // Od której rundy ma dostawać
```
</details>
