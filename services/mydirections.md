# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

- Used https://www.epochconverter.com/ to pick a departure date sometime after the program ends
- Used https://developers.google.com/maps/documentation/utilities/polylineutility to encode polyline
- Used https://developers.google.com/maps/documentation/places/web-service/place-id to find place ids

## Directions URL

*Possible Bike Packing Trip for the Summer*

https://maps.googleapis.com/maps/api/directions/json?departure_time=1656676800&origin=place_id:ChIJxbfQ7E2LK4gR_8s0OX1AoeM&destination=place_id:ChIJT2TscKHYKYgRdDZj0cyy_RM&waypoints=place_id:ChIJk0UzV4SVK4gR1vGNrg6VNhM%7Cenc:g%7dunG~upoN%7dhIacI%7blJ%7bjE:&avoid=tolls%7Chighway%7Cferries&mode=bicycling&unit=metric&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE


## Next paste the full JSON response to this query here:
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJxbfQ7E2LK4gR_8s0OX1AoeM",
         "types" : [ "establishment", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJk0UzV4SVK4gR1vGNrg6VNhM",
         "types" : [ "establishment", "park", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJcRCrDuTPKYgRpkt2xF6SYOA",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJFW7hKUnaKYgR97_mkuhtvoc",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJE087et_YKYgR84KL0hjTkTQ",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJT2TscKHYKYgRdDZj0cyy_RM",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 44.67406159999999,
               "lng" : -80.41812659999999
            },
            "southwest" : {
               "lat" : 43.4602311,
               "lng" : -81.38868050000001
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "29.3 km",
                  "value" : 29295
               },
               "duration" : {
                  "text" : "1 hour 33 mins",
                  "value" : 5562
               },
               "end_address" : "Elora Gorge, Elora, ON N0B 1S0, Canada",
               "end_location" : {
                  "lat" : 43.6604309,
                  "lng" : -80.4545363
               },
               "start_address" : "Grand River South, Kitchener, ON N2A 4G3, Canada",
               "start_location" : {
                  "lat" : 43.4602311,
                  "lng" : -80.42009879999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 43.4602987,
                        "lng" : -80.4201939
                     },
                     "html_instructions" : "Head \u003cb\u003enorthwest\u003c/b\u003e toward \u003cb\u003eEbydale Dr\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOtterbein Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mighGr`ziNMP"
                     },
                     "start_location" : {
                        "lat" : 43.4602311,
                        "lng" : -80.42009879999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1125
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 250
                     },
                     "end_location" : {
                        "lat" : 43.4661268,
                        "lng" : -80.4306988
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOtterbein Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{ighGdaziNQSCCE?G@CBCDy@dBi@fACDsArBCLERId@CPIf@Gb@Kd@EJENKRMTQVQRED}@x@ULOHgAh@[RSRa@l@o@jA_@r@o@fA_AbB]l@Yf@INITCDYz@w@hC}@fBa@p@]z@SlAIpAQrCQdC"
                     },
                     "start_location" : {
                        "lat" : 43.4602987,
                        "lng" : -80.4201939
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 207
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 43.4673519,
                        "lng" : -80.4323215
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003eOtterbein Ct\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "inhhGzb|iN?VA\\CPU|@G\\ENM\\ABEBQNMLMDA@QBMFOJGDGBcA`@"
                     },
                     "start_location" : {
                        "lat" : 43.4661268,
                        "lng" : -80.4306988
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 869
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 157
                     },
                     "end_location" : {
                        "lat" : 43.47074,
                        "lng" : -80.440685
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "}uhhG~l|iNGFE@MDELGJI?EGKCE@U\\Ub@G^Id@OTOT]N_@DYFMDKLo@fAGJeAlBQZIPWb@i@~@KLMLYR]PMLGJELAT?TDVLf@JZ?@BLBR@N?PAVEh@[jDU`DI`AYnDGx@Ax@"
                     },
                     "start_location" : {
                        "lat" : 43.4673519,
                        "lng" : -80.4323215
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 125
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 43.4717777,
                        "lng" : -80.44127759999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLackner Blvd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ckihGfa~iNw@d@C@c@ToBx@"
                     },
                     "start_location" : {
                        "lat" : 43.47074,
                        "lng" : -80.440685
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2251
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 398
                     },
                     "end_location" : {
                        "lat" : 43.4824586,
                        "lng" : -80.4180374
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVictoria St N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-7\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sqihG~d~iN{@eDQs@EQ{@gDKe@k@_CU_ASu@Ke@Sy@]sAa@aBMg@cAeE{@kDo@kCCK_AwDi@wBs@wCWeAK[Sw@Uy@W{@[aAe@kAi@iASa@e@w@_@s@Ye@y@uA{@yAQ[Ye@_@w@GKUk@[s@Sk@Si@ACg@aB_BoFW}@Ww@EOQg@kBeG]mAe@_BGSYw@Wy@Ys@Qa@Q_@QYOYSW_@e@EG]_@c@a@WUQMUOUMQKQIi@W"
                     },
                     "start_location" : {
                        "lat" : 43.4717777,
                        "lng" : -80.44127759999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.4 km",
                        "value" : 3397
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 679
                     },
                     "end_location" : {
                        "lat" : 43.49449920000001,
                        "lng" : -80.4534518
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eEbycrest Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWaterloo Regional Rd 17\u003c/b\u003e (signs for \u003cb\u003eRegional Rd 17\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eEbycrest Road\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ktkhGvsyiNOj@EPKVGJGFEBGDIBKBG@KAGAKC]UqA_AECMIUIMCO@SDUJSRU\\g@xAcBlEcAnCeBrEuGbQADs@vBuAdEc@vA{@jDq@|CWhAQ~@aAdFY|ACNSjAe@jCKj@e@nCGj@e@lDANS|Ac@|Fa@lI[tFi@fKKzBIbDC~EBnA@zCJhCD|A@Z@X@x@?h@?j@?B?@Ej@Ch@M~@In@Mf@?BMb@AFOb@A@Q`@a@x@{@dBU`@ABoBxDABUf@CDmEfIABkAvBSb@IXCDADAHCPAPCp@"
                     },
                     "start_location" : {
                        "lat" : 43.4824586,
                        "lng" : -80.4180374
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.6 km",
                        "value" : 4611
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 847
                     },
                     "end_location" : {
                        "lat" : 43.5319757,
                        "lng" : -80.4750634
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSawmill Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWaterloo Regional Rd 17\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "s_nhG`q`jNWLe@ROHQH_@RaAh@_@RSJKFaCtAa@T_@RMHq@^gLpGkFvCy@b@CB{@f@_B`AsBnAOJaDjBMHQJQJo@ZaAh@WNA?[PaDdBEB{C`BqC`Bq@b@MFu@^YLu@TsA`@_IxB}Af@qCx@wCj@eCVsBLiG^}Gd@sDV}Gd@mLx@c@By@Fo@Lq@LeAb@QJc@VuHlF{CxB}B~AaBjAmHlFqA`AQLaAx@kEhD}B`CwBjCe@p@CDcB`CGFU`@m@~@EDeAbBEDS\\CDqDtF"
                     },
                     "start_location" : {
                        "lat" : 43.49449920000001,
                        "lng" : -80.4534518
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "6.1 km",
                        "value" : 6139
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1130
                     },
                     "end_location" : {
                        "lat" : 43.5863806,
                        "lng" : -80.4668461
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKatherine St S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWaterloo Regional Rd 23\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{iuhGbxdjNYEeAOc@GuEm@cG{@iBY{AUyDm@_O}B{GcAmCc@yGcAc@IqDk@mCa@a@GiBWwAUeFw@e@GkCa@wPgCiBYmCa@gAOa@GoEq@aC]aJqAcFw@c@GwF{@qDi@a@G}@M_@Ga@GaBWeAQiAQc@Ga@ESEy@MeAOc@IeAOc@Gc@Ic@GeAOeAQc@Gc@IeAOc@Ie@GmCa@mCc@a@Gc@GeAQc@GsEs@c@Gc@GmFy@kCe@}M{BiBKyDXcBVwFx@c@FiBXc@FiBVsEr@mC^c@HeBVg@F{Gv@oC\\u@Hg@B}D^c@Dk@F{BHkASEC_C{@"
                     },
                     "start_location" : {
                        "lat" : 43.5319757,
                        "lng" : -80.4750634
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1212
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 192
                     },
                     "end_location" : {
                        "lat" : 43.5852288,
                        "lng" : -80.48110869999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRivers Edge Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{}_iGxdcjN[xAOl@Ml@Mj@Ml@e@vBQ~@Q|@InAEp@KrAA~@?DDh@Dn@Ll@Nl@H\\DLRf@Rh@b@dABJLl@Lf@TbBHn@R~AHl@Hn@BLD`@Fn@Fp@Hn@Fn@N~ADb@@J@p@@p@@r@?n@@`ER`CRz@z@nE?FDp@"
                     },
                     "start_location" : {
                        "lat" : 43.5863806,
                        "lng" : -80.4668461
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 193
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 59
                     },
                     "end_location" : {
                        "lat" : 43.5867238,
                        "lng" : -80.48228739999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCovered Bridge Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uv_iG|}ejNMVAB[T[Rq@b@q@b@_@V}@l@_@V"
                     },
                     "start_location" : {
                        "lat" : 43.5852288,
                        "lng" : -80.48110869999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 658
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 140
                     },
                     "end_location" : {
                        "lat" : 43.5924829,
                        "lng" : -80.4804772
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eCovered Bridge Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_``iGhefjNuBw@yBq@mBi@oBk@YGuCm@mCk@a@IICuBUcAKgAKa@Ec@E"
                     },
                     "start_location" : {
                        "lat" : 43.5867238,
                        "lng" : -80.48228739999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8.5 km",
                        "value" : 8497
                     },
                     "duration" : {
                        "text" : "27 mins",
                        "value" : 1629
                     },
                     "end_location" : {
                        "lat" : 43.6604309,
                        "lng" : -80.4545363
                     },
                     "html_instructions" : "Continue onto \u003cb\u003e62 Township Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMiddlebrook Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTownship Rd 62\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Middlebrook Rd\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "polyline" : {
                        "points" : "_daiG~yejNiBQqD[gAKoCWC?eHu@c@GmCYSCOAiBUc@EmC[c@EmC[c@GmC[gAMgAMeAMgAMc@Ea@EgAMc@Gc@Ea@GoC[yC]cAGu@BI@iBPkBTa@D{C^qD`@c@DmCXiBR}Gr@iALiAJc@D}@HoAP}C`@SHa@LqBr@yAj@eBp@a@Na@PcA^cA`@a@NcA`@WJGDa@PgDzA_@PeBt@_@RWJIDa@Na@Pa@Na@PSJKBc@NgCz@eA\\a@La@Nc@NkAb@WD_@FC?c@?c@?c@?gA?c@?c@?oC?c@?gA?i@?mDF{@@wBAM?UCc@Ca@ESAs@Mc@Ia@Ic@Ia@Ic@Ic@Ga@Ic@Ic@Ia@Ic@IiB[a@Ic@Ic@Ia@IiB[gASa@ISCa@Y[w@i@oAUi@Sg@Ug@Sg@Ug@Si@c@eAa@g@EG{@_@]Oe@Oc@Ka@Ma@Mc@KcAYc@Ma@MgBg@a@Kc@McAYc@Ma@Ka@M_D}@MCcA[c@Ma@McA[c@Ma@MiCw@gBi@yEyA}Bu@QEOEeAYmD}@c@KmCq@]Oq@WkAiBq@gAYa@Wc@Yc@Wc@Ya@Wc@IMOUYa@[a@Ya@Ya@OUU]KQYc@Wa@Yc@Yc@Wa@Yc@q@eAYc@{@sAs@cAYa@s@cAYa@Yc@s@cAYa@yCkEwGaKiIgMYa@wCsECCaBiC{FaJ}BqDcBmCqAuBiBsCqDwFwBiD"
                     },
                     "start_location" : {
                        "lat" : 43.5924829,
                        "lng" : -80.4804772
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "138 km",
                  "value" : 138289
               },
               "duration" : {
                  "text" : "7 hours 9 mins",
                  "value" : 25731
               },
               "end_address" : "900a Bruce County Rd 13, Southampton, ON N0H 2L0, Canada",
               "end_location" : {
                  "lat" : 44.5181494,
                  "lng" : -81.3555049
               },
               "start_address" : "Elora Gorge, Elora, ON N0B 1S0, Canada",
               "start_location" : {
                  "lat" : 43.6604309,
                  "lng" : -80.4545363
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 320
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 43.6584142,
                        "lng" : -80.4573733
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e on \u003cb\u003eMiddlebrook Rd\u003c/b\u003e toward \u003cb\u003e3 Line W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ulniGzw`jNvBhDpDvFhBrC"
                     },
                     "start_location" : {
                        "lat" : 43.6604309,
                        "lng" : -80.4545363
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8.2 km",
                        "value" : 8199
                     },
                     "duration" : {
                        "text" : "29 mins",
                        "value" : 1730
                     },
                     "end_location" : {
                        "lat" : 43.7105034,
                        "lng" : -80.5290521
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e3 Line W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a`niGpiajN_@h@q@bAY`@Yb@mAdBYb@{ClEYb@U\\[d@mAhBW`@gBjCWb@Y`@Yb@s@dAW`@Yb@Y`@Yb@q@dAY`@Y`@q@dAYb@Y`@Yb@kAfBYb@s@dAW`@Yb@Y`@Yb@q@dAY`@s@dAWb@Y`@Yb@Y`@q@dAmAfBYb@W`@Yb@Y`@Yb@Y`@Wb@Y`@Yb@Y`@Wb@s@dAs@dAW`@Yb@Y`@Yb@Y`@Wb@Y`@Yb@s@dAW`@Yb@Y`@Y`@Wb@Y`@s@dAYb@W`@c@n@W`@Yb@s@dAkAhBY`@Yb@W`@s@dAYb@qDrFeBjCYb@wG~Js@fAY`@kEvGYb@eBjCW`@Yb@Y`@Yb@W`@Yb@eBjCY`@Yb@CFm@~@W`@cBnCYb@Yb@q@dAWb@Yb@Wb@gE|G}BpDcBnCW`@cBnCyCrEq@dAcF|HY`@q@fAY`@cBlCkAhBYb@q@dAs@dAWb@s@dAWb@Yb@kAfBYb@}BnDYb@}BnDYb@q@dAkAhBYb@Yb@W`@Yb@q@dAYb@kAhBY`@]j@eA`BY`@s@dAYb@q@dAY`@q@fAeBjCmAfBwCrEs@dAyA|BuJ`OY`@q@dAkAhByCpEYb@Y`@q@dAYb@Y`@Yb@q@dAY`@Yb@W`@s@dAYb@Y`@eBjCeBjCYb@W`@Yb@Y`@Yb@W`@A?S\\CDY`@kAhBY`@yG`KkAfBW^_@^]PC?_@Fe@J{@RGD[R_@b@Od@ADKl@A@Gl@In@EZCRKj@?@Yr@QXYb@Y`@Y`@s@dAW`@Yb@Y`@w@jA"
                     },
                     "start_location" : {
                        "lat" : 43.6584142,
                        "lng" : -80.4573733
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1467
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 315
                     },
                     "end_location" : {
                        "lat" : 43.7198783,
                        "lng" : -80.5162059
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWellington 17\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sexiGpiojNc@o@Wa@Yc@eBkCs@eAq@eAs@eAqDuFeBkCYc@mEyGcBiCwCsEkAiBqB}CuFiImIcM"
                     },
                     "start_location" : {
                        "lat" : 43.7105034,
                        "lng" : -80.5290521
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12.8 km",
                        "value" : 12773
                     },
                     "duration" : {
                        "text" : "38 mins",
                        "value" : 2280
                     },
                     "end_location" : {
                        "lat" : 43.7763596,
                        "lng" : -80.65465309999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e12 Line\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g`ziGhyljNsAxEQj@a@vAOj@Od@Sp@Qh@Oj@Qh@Qj@Qj@Qh@gAlDQh@wAxEQh@Qj@Qh@Qj@iBbGQh@IVGR]zACLuB`HQh@eAlDyAvEOj@yAvEs@`CQj@Qj@Qh@Qj@eAlDc@tAOj@Qh@]jAWt@s@bCc@tAQl@{AdFc@vAOh@Qj@a@vAQh@Qj@s@bCQh@Oj@c@vAOj@s@`Cc@vAQh@cAlDeAnDQh@Qj@Oj@c@vAOh@eAlDQj@Oj@Qj@Qj@Qh@Oj@s@bCc@tAOj@Qj@Qj@Qh@s@bCOj@Qh@Qj@Oj@Qj@a@tAeAlDQj@a@vAQj@uAxEQh@wAxEOj@c@vAs@`Cs@bCOh@Qj@Qj@Oj@Qj@Qh@Oj@s@bCQh@Qj@Oj@eAlDQj@a@vAQj@AD_@nAQj@eAlDQh@gAlDOj@Qh@iBdG{BnHQh@wAxEa@tAQj@Qj@eAjDc@vAQj@Oh@Qj@oAdEeDxKoAbEwAxEeAlDs@`Ca@tASn@wBjHu@`CQj@a@vAQh@Qj@gBbGQj@eAlDu@`CQj@a@tAQj@wAxEQj@kCxIa@vAwAvEQj@c@vAGTS\\_A~CQh@wAxEQj@yBlHc@tAgAjDgAjDSj@yAtEuDlLQh@IVQl@Wz@Qj@u@`CwAvE{BnHc@tAQj@eAhDABc@tAcD`KqGbSQh@c@tA{AtEs@zB{BnHgAjDeFrPQh@{BnHc@tAu@`CmCxIqDpLQj@s@~BQj@gAlDQh@Qj@s@`Cu@`CQj@c@tAaEzMuB~GeEbNUp@Qh@cD`KQj@Qh@Qj@Qh@Qj@e@tAITGRa@vAQj@iBbGQj@eAlDOh@_@jAg@`B_DvJCHmCzI{BlHQj@c@tAk@jBe@|AELQj@Qh@]hAWx@eAjDu@`C"
                     },
                     "start_location" : {
                        "lat" : 43.7198783,
                        "lng" : -80.5162059
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "32 m",
                        "value" : 32
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 43.7766094,
                        "lng" : -80.6544433
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWellington County Rd 11\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gaejGpzgkNq@i@"
                     },
                     "start_location" : {
                        "lat" : 43.7763596,
                        "lng" : -80.65465309999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "5.3 km",
                        "value" : 5337
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 976
                     },
                     "end_location" : {
                        "lat" : 43.8002724,
                        "lng" : -80.7122249
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eConcession Rd 12\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ybejGfygkNQf@Qh@Qh@y@~BQh@Sh@Qh@Sj@Qh@Qh@Sh@w@~BSh@IVGPQj@Qh@Qj@Sh@Qj@Qh@Qh@Qj@Qh@iAjDQj@c@tAe@rAGVIRuAxEQj@Qj@Oh@u@bCOh@Qj@Qj@a@vAwAxEOh@eAlDQj@wAxEOj@wAxEeAlDQj@yBnHQj@Oj@Qj@yBnHqEhOQj@s@`CQj@s@`Cu@bCOh@Qj@eAlDQj@iBbGOj@y@lCK^Qj@sAzEQj@Oj@Qj@s@bCOj@s@`COj@IXGPOj@s@`CQj@Qj@Qj@Oj@Qj@a@tAc@vAOj@Qh@Qj@s@bCa@tAQj@s@bCQh@Oj@sApEkBjGu@`COj@Qh@wAxE{BnHs@`CeAlDgAlDOj@c@tAkCzIiBdGwAvEQj@Qj@Qj@Qh@Oj@Qj@u@`COj@c@tAeAlDQj@Qh@Qj@Mb@CFUd@GLq@h@"
                     },
                     "start_location" : {
                        "lat" : 43.7766094,
                        "lng" : -80.6544433
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 365
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 119
                     },
                     "end_location" : {
                        "lat" : 43.7993633,
                        "lng" : -80.71653859999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWellington 10\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uvijGjbskNNl@H\\BLHZL`ADRJ~B@PB^F`BDp@Bn@@NDv@N`ALl@^`ANb@"
                     },
                     "start_location" : {
                        "lat" : 43.8002724,
                        "lng" : -80.7122249
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.9 km",
                        "value" : 3902
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 649
                     },
                     "end_location" : {
                        "lat" : 43.81756800000001,
                        "lng" : -80.754784
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eConcession Rd 12\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_qijGj}skNm@KKCWEOCm@i@][][]Y_@]{@q@WUECYKQBO\\gAlDs@`CQh@qDpLa@tAgAlDQj@{BlHwAxEkBbGeAlDu@`Ca@tAQj@u@`CQh@Qj@Qj@Oh@c@vAQj@Qh@eAlDyAvEQj@a@tAu@`Cc@vAs@`CQj@u@`Co@tBiAlDQj@iAjDY|@}@xCQj@kCxIQj@iBdGwAvEQj@Qj@oDpLaA`DkAxDQh@s@`CQj@gAjDQj@c@tAQj@eCbIk@jBQj@s@`CQj@Oj@Qj@u@`Cs@`C"
                     },
                     "start_location" : {
                        "lat" : 43.7993633,
                        "lng" : -80.71653859999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1355
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 247
                     },
                     "end_location" : {
                        "lat" : 43.8282677,
                        "lng" : -80.74669159999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSide Rd 3\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ybmjGjl{kN}B}A}AgA_@W_@W}@o@wR}M_@W}CuB_@W{F_E}AgA_@W}CuB_Ao@_@W{EgDwAaA"
                     },
                     "start_location" : {
                        "lat" : 43.81756800000001,
                        "lng" : -80.754784
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2130
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 437
                     },
                     "end_location" : {
                        "lat" : 43.84487439999999,
                        "lng" : -80.75914399999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWellington Rd 7\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ueojGxyykN_A`Dc@jA]x@KTg@`Am@~@cAnAMNML_Az@k@ZwL|G_@TOHuGrD_@RaAh@OHOJaB~@OHOHcFrCOHaB~@QH_@ToAr@QJMFQJeIrEOHqAr@oAt@q@^oAr@uEhCo@\\aH|DuAt@a@Fa@F"
                     },
                     "start_location" : {
                        "lat" : 43.8282677,
                        "lng" : -80.74669159999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "9.9 km",
                        "value" : 9948
                     },
                     "duration" : {
                        "text" : "28 mins",
                        "value" : 1673
                     },
                     "end_location" : {
                        "lat" : 43.9025983,
                        "lng" : -80.8509406
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit onto \u003cb\u003eWellington County Rd 109\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "mmrjGrg|kNAAAAAAAAAACAAAA?AAA?C?A?A?C?C@A@A@C@A@A@A@?@ABA@AB?@AB?B?B?@y@`AMNo@`@MHgAn@wF`D[PuGtDa@TcJfF_Aj@e@V}CfB_@R_@TaCrAcCtAaDhB_@TaCrAaAj@_Ah@a@T}CdBcAl@{BnAeAr@cAx@k@j@c@f@k@l@WTONa@d@QVmAlB]j@i@~@aDjHO\\mBrEwHtQSf@_AvB}ClHsDvIUf@Wj@cLbXSf@}DjJuA`D{BlFy@nBw@hBUf@gFzLKR_@z@GNsHlQyAlDy@lBeHtPUf@[r@gFzLoIfSUf@{FdN{CfHoIfS}FbNqIfSqCxG}FdNSf@eExJMZEJw@jBQ`@m@vAgDbI{GbP{E~KkKpVwIpSOZoBtE}FbNGL[t@eAdCuD|ISh@{FdN}DjJs@`A"
                     },
                     "start_location" : {
                        "lat" : 43.84487439999999,
                        "lng" : -80.75914399999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2061
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 374
                     },
                     "end_location" : {
                        "lat" : 43.9133708,
                        "lng" : -80.8716968
                     },
                     "html_instructions" : "At the roundabout, continue straight to stay on \u003cb\u003eWellington County Rd 109\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "gv}jGjenlNC?A?C?C?A@C@A@C@A@ABCBCDAB?DAB?BAB?B?D?B@B?D@B?B@B@@S|@_@|@oGdOsEpK_@~@s@bBUf@i@nA}BnF_DnHuAjDsA|CYp@i@nA_AvBkCnG{AlDi@nAuA~Cg@hAk@lAi@nAWl@k@pAi@nAaAvBg@jAi@pAkAzCYv@"
                     },
                     "start_location" : {
                        "lat" : 43.9025983,
                        "lng" : -80.8509406
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13.4 km",
                        "value" : 13420
                     },
                     "duration" : {
                        "text" : "39 mins",
                        "value" : 2339
                     },
                     "end_location" : {
                        "lat" : 43.9842067,
                        "lng" : -81.00741649999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eElora St N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-9\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow ON-9\u003c/div\u003e",
                     "polyline" : {
                        "points" : "qy_kGbgrlNIPi@nA{@lB_AxBSf@}@xBi@nA}@vBsAzCABiBjEoAtCcA~BoBtEq@~A{@tBi@nAEHO^MZGJ?@}@tB{BjFqCxGaFpLEJgF|LaDtHEL[r@}CfHwB~E}BpFUf@Uf@_CpFi@nAUf@Sf@Uf@_AxBk@nA}DjJSf@_EhJ}FbN_CpF}BpFiBhEUf@i@pAsErKuA~CsCzGsB|EeD|HSf@CDcHnPCFQ`@gDbIgD`IyAjDUf@sCzG_AvBmBrEiDbI_AvBsA`DuCxGSf@Uh@}FbNoCxGaHxP}FdNi@nAsA`DSh@}H|QgBhEUh@sCxGSf@}DlJ}BpF}DjJ{DfJUh@Sf@Uf@}BrF}BpFUf@_AxBSf@}DlJSf@uA`DSf@sA`DsA`D_CrF}@xBUf@Sf@_AxBi@nASh@_AvBUh@}BpFgBhEUh@mArC{DjJ_AzB[t@_BzDqA`DGN_AtB_AvByA`Di@nA[p@i@rAsA`DMZa@`AeAdCWl@_AvBuA|CgBjEi@pAEHo@zAi@pASd@?@Uf@Sf@A?Sh@i@lAUh@}@vBA@}BpF_AxBoAvCy@nBiAnCSf@_AxBkBpEgAfCqCzGi@nAUh@gBhEi@pAiBhESh@sCzGqCzGUf@i@pA}BpFSh@sA`DUf@Sf@gDdIsCzGi@nASh@}ArD"
                     },
                     "start_location" : {
                        "lat" : 43.9133708,
                        "lng" : -80.8716968
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1660
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 296
                     },
                     "end_location" : {
                        "lat" : 43.9812168,
                        "lng" : -81.027738
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHuron Bruce Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "itmkGjwlmNFn@d@rFN`BFr@VdDN`BDn@N`BL`BTrCFn@Fp@Dn@BXVhDBX\\zEFn@Dp@x@fKDn@Fp@Dn@Fp@Dn@Fp@L`BDp@Fn@Dp@Fn@Fp@ZbEPxBFp@Dn@Fp@Fn@\\bEDp@N`BDn@N`BJvAR|C"
                     },
                     "start_location" : {
                        "lat" : 43.9842067,
                        "lng" : -81.00741649999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "19.0 km",
                        "value" : 19029
                     },
                     "duration" : {
                        "text" : "58 mins",
                        "value" : 3501
                     },
                     "end_location" : {
                        "lat" : 44.1151586,
                        "lng" : -81.1550944
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBruce County Rail Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "samkGjvpmNq@fAq@dAOVGJYb@eBlCWb@kAhBq@fAeBlCkAjBq@dAqDxFWb@Y`@}BpDYb@Wb@Yb@Wb@m@|@EF{BrDYb@Wb@Yb@q@dAYb@Wb@q@fAkAjBq@fAcBlCgAfBiAtBoAbCgApCSh@Sh@EJMZ}@zBQf@Uf@g@rASf@Sh@Sh@}@zBSf@{@zBc@fAm@zAi@rA{@xBUh@eBlESf@i@pA{@zBUf@Sh@_AxBqA`De@hA]h@}@tAk@p@w@~@]`@{BxAYRiAb@_A\\g@LeAV[HiB`@CBs@l@GHY`@[`@OT_AlA_@d@S\\uCvEq@fAq@fA}BpDq@fAOXGHs@fAWb@s@dAWb@Yb@Y`@Wb@Yb@U^s@jAWb@q@fAcBpCWb@aBnCeBtCU^uCvEeBnCWb@Yb@s@hAq@fAq@fA{BpD}BrDa@n@sBfDc@t@_AvAYb@u@hAs@|@oBhCkBnB]`@]\\[\\_@^wAnAMLeAlAsA|AwBdCSXs@bAY`@EDiA|Bs@fBUf@Sh@Wl@o@~AcAnCUf@Sh@g@pASh@Sh@Sf@{@|Bi@pAg@pAcBnEeBlE{A~D[x@eBlEqAdD{@zBSf@mA|C}@dC{@zBe@rAk@|AK`@Ol@Oj@m@fCMl@Ox@]nBQ~@wAfIQ|@m@jDMl@kAxGMl@Oz@a@~Bc@jCW|AY|ACRUhAMl@Ml@I`@CJa@vAOj@CHu@tBc@hAEFw@fBcBhDeAvBk@hAyAzCUd@Uf@eAvBSb@Wd@Ud@m@lA[n@_AhBcArBSb@o@nAWf@Ud@EHQZ}AtCWd@W`@?@[`@Y`@Y`@QTc@j@EDu@r@[\\]Z[\\EDWT]Z]ZIFQTQRIJY`@w@fASh@m@tASh@Uf@IP]~@e@rAg@rAg@rA{@`CeAjBKPe@r@u@dAKPOJ{@r@SNKF_@RULm@Ta@Na@Na@Nk@RgFvAeAXgBd@mD`Ac@Ja@LuCt@y@Tc@Ja@Jc@LcAViBd@eAVa@JA@eCz@_AZe@VcAh@aBjAw@n@m@d@eC|BoEdE]ZCBYVy@x@sClC]ZwAtA]\\wArA]\\]Zy@v@{@v@]ZYXuAfAWTaAv@y@l@_@VYTC@a@T_Al@_@TULIDcCpAaAf@mCtAw@`@eFjCeDbB_@RaAf@eDbBgG~CcEvBeDbBaBz@aAf@a@RYNgAl@aB|@aAh@mAp@yB|@eCbAuBj@{AXgAPoDp@eAPc@Hk@JYFwF`AeARmCd@a@FmCd@c@HkCd@c@HeAPE@aAPeARc@Fa@HgARcBXE@{HxAyGnAoDp@gARgB\\gARiB\\a@HA?a@Fa@Hc@Hc@HeARc@Ha@Hc@Hc@Ha@Hc@FuFdAeARA?a@HeAPc@Hc@HoDp@c@HsCh@gLtByB`@yAVa@HgARa@HiARgARc@Hc@H]FC@c@HoDn@oDp@sDn@_@Hc@Hc@FiB\\qEx@cC`@m@JeARmCb@wF`Aa@FgARkCb@c@Hq@Jw@NwB^c@Hc@Ha@Hc@HmCd@{HtAA?a@F{GhAeAPo@Jy@NgAPKBUH{@XiAj@a@Rs@^iA|@]X[VC@[^]^s@~@"
                     },
                     "start_location" : {
                        "lat" : 43.9812168,
                        "lng" : -81.027738
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 222
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 92
                     },
                     "end_location" : {
                        "lat" : 44.1148001,
                        "lng" : -81.15783329999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKincardine Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-9\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wfglGhrinNJnA`@jGXfE"
                     },
                     "start_location" : {
                        "lat" : 44.1151586,
                        "lng" : -81.1550944
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 377
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 44.1177679,
                        "lng" : -81.1596565
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWallace St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "odglGlcjnNaFv@wCj@g@LU^mAnBkAjB"
                     },
                     "start_location" : {
                        "lat" : 44.1148001,
                        "lng" : -81.15783329999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "44.0 km",
                        "value" : 44048
                     },
                     "duration" : {
                        "text" : "2 hours 20 mins",
                        "value" : 8396
                     },
                     "end_location" : {
                        "lat" : 44.427581,
                        "lng" : -81.38868050000001
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBruce County Rail Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "awglGznjnNML?@MDO?MCIEOGKCIAKDGBm@z@_@j@o@x@o@|@w@jAq@dA_CpD}BpDe@r@MPqCjEEFq@fAq@hAQh@s@bCOj@Ml@Mn@Ml@GXc@bD?@WbEYdEYbE]vFGn@IvAa@`G_@tFQrCSrCKbBK`BEp@QrCM`B]vFQpCMbBK`BYdEQrC_@tFKbBYbEk@xIWdEGn@Ep@C`@Y`DO`BC`@e@zCYfBi@~Bg@~Bg@~Ac@vA]hAYt@Sf@o@|AM\\u@rAWd@o@hAEFuCfEaClDgBhCuDrFs@bAYb@Y`@gBhCaClDgBjCs@bAWb@Y`@mAfBORgBjCY`@Yb@Y`@mAfBs@dAq@dAmAfBs@dAaCjDW^{A~BKNYb@s@dAmAfByCpEsDrFaClDs@dAq@dAgBjCYb@Y`@Yb@kAfBiA`BkAhBUZiClD[^qBlCs@n@wD~CSPoBv@cAb@cA`@C@kDp@yAXq@LsEx@oDn@mCd@c@HsEx@oDn@oDn@m@JiEv@eARiBZoDp@mCd@a@Hc@HkCd@mCf@iARiARmCf@eARc@HeAPsEz@eAPc@Ha@Hc@HeARc@Hc@FkCf@iB\\oDn@gARgBZgARkCf@c@FeARiB\\c@HoDn@iB\\eARmCd@sEx@oDp@eAPeARmCf@iBZc@Ha@Hc@Hc@H_@FA@eARc@H[FG@a@HaGfA{B`@OBgATgB\\gAReATeARu@NOBc@HkCf@c@HiBZc@HkCf@QDwAViB^a@HiB\\c@Hc@H}AZI@c@Hc@Ha@HqDn@a@Hc@Fc@HyB`@QDc@HeAReARiB\\c@H{HzA_Dl@s@LkCf@sEz@wFdAkCf@eARiB\\gBZe@Ja@FiB\\gARiB\\a@HUDo@Jc@HeARc@HiB\\c@HA?gBZa@FsEv@iBZOBaDl@eARa@HmCd@c@Ha@Hc@HoDp@kARmEx@oDn@qDn@oDn@c@HwDr@mCf@iB\\_@HoCd@c@HiBZc@FwAVs@LOBeBHY?c@?eAAuAE{@I_@CoCi@EAeCo@qFwAc@K}JkCeAWkCs@q@Q}Cw@oBg@aBc@eAYkD_AiBe@mD_A}@WwO_EqA]UGc@MgBe@a@MgBe@kCs@a@Ma@KmD_AiBg@cAYc@K_Bc@aD{@c@Ma@KgBg@kD}@AAeAYa@KoA]cCa@eAQICaBEgACC?_@?y@Aq@Bc@BY@k@LuFfA}Bd@q@LwF`AyGlAc@Hc@FkCf@c@Ha@Fc@HmCd@?@OBc@HYFoATIBy@VuGlBsGlBoEpAa@La@LwHzBiCv@iCv@c@JcAZg@N_AX[JgBh@c@La@La@LgBh@qF`B}Ad@qBl@eBh@eAXeAZeBh@mDbAqF~A_@LkCx@a@NA?_Ah@kAp@mAlAk@h@aAtA[`@CD_AlBe@`AwApDkCdHsDtJoAfDcBnEsCxHgApCwBxFg@rA{@|Bw@rBSh@cBnEsDvJ[z@sAfCUd@g@`AaAfA}@dAu@l@u@n@kBx@kDjAkDhAa@Na@LgBl@mExAa@NoBp@y@\\a@NcFvBEDwD|C}@t@{@r@EDqArAuArAABYX[X]XYVCB]XEBu@l@QNKFIDUN_@RgAp@WJ_@LOFQFw@Xk@Ra@LQFODa@LcA\\UHa@NaA^YJGBA?_@LA@_@La@NA?eCz@a@NC@gA^_Cz@_DlAeCz@_Ab@k@b@aA`Ae@j@Y\\g@~@S`@Wp@M\\GVABKh@Ml@Kn@EPE\\CV?BGp@AHEd@AJGd@AHEd@AHEf@AHGd@AHEd@AJEd@AHGf@?FGf@[zCCf@W|CCf@A@?DCp@Cr@@f@HtCDpABbABjB@h@?FBp@@p@@h@?FBp@@h@@f@@R@f@?HBf@?H@h@?F@h@DbB?FBh@?F@h@@p@@FBzAH|CFlC?HFlC?FNpGBbAJ|CDzAFjB@p@Bp@?FElCGhEAz@C^?FSrCIfAAPUfBIf@?FIf@CVg@zBMl@Kd@AFENY~@c@zAUj@Qb@y@xBCHQ`@Yl@Q`@m@tAWf@Uf@Q^Yl@Sf@S`@Wl@S`@cA|BcAvBSd@wA~CABi@jACBg@jAo@tAQ^}AhDO\\uBrEMXs@|AyA`Da@|@IP[r@EHIRa@z@KRUf@IRUf@a@|@INKVINKVINMVGNc@`AUf@GLMXGLMXGLUf@gBzDEHO^yA~CAF_ApBABUf@Sb@Uf@ABUd@k@nAUf@?@Ud@?@Uf@u@`Ba@z@A@oBhEQ`@CDiB`ECFg@fAEFO^k@lAEJO\\EHM\\EJOZELs@`Bo@jAo@hACDuBnCKNiAxA_CnBaBdA_An@_BbAc@X}B|AcBdA{AbA_HnE_@V_@V_F`DiHvEsBrA_C|A_DrB}FxD_@V_BdAk@^sBrA{@j@gFfD_F`D_CzA_BdA_BbAuDdCi@Z}CrB_EjC_DrB}DjCiCbBu@f@_C|AiAt@wAt@iCxA_DjAA@mDp@E@iDRA?gA?w@?OAc@CgAEeAGeAYkCu@SGo@WcBs@IEy@]eBu@aAc@oCiAWMcAc@iEmBgEkBiEkBcBu@k@WmBy@kFyBe@S_Aa@a@SqAk@s@[aAe@m@Wu@]iEoBcBu@eCiAeCiA_DyAECa@Qa@Q_@QcAe@aAc@gD{AeCiAa@QeCiA{BcAqCeAi@SaDeAA?qE}@mCi@oDs@oDs@q@Ow@M}Cg@cMqBsBKsBK{CJOB}C\\wA`@iAZ_A\\mAd@uA|@iBhAq@p@oDlDuA|AqBxBKJgApAsA|AEDaC~CA@oBfEOd@{@fCq@zB{BpHyAzEeAnDeFvP{@pCK\\iBdG_DhKu@`CeBbFMZeAzBgAdBi@|@]f@q@dAy@|@[\\QRkAx@]XoA~@m@`@_EjC}B|A_@V_BdA_@V_@T}CtB_BdA_BdA_@V_@V]V_@T_@V_An@_@T_@VaAp@o@`@OJ}F|D}B~A_ElC}EdD}@n@EByCpB}@n@_Al@_@V_@V_BdA_@V}AfA_@V_@T}CtB_@V}DlCWPgBlA_An@u@h@cBrAOJgAjASTGFuA|AABs@|@gCbDmB`C[`@Y^qGfIgCbD[^Y^?@w@`AyAlByAjB[`@Y^[`@mB`CaDdEmBbCkBbC[^Y`@iCbDY^mBbCY`@gCbDqA`B[`@}DdF[^gCdDY^KLgArAY^aAjAOTmAdBA@i@jA]lAOx@Kd@QpAGjAEn@"
                     },
                     "start_location" : {
                        "lat" : 44.1177679,
                        "lng" : -81.1596565
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7.5 km",
                        "value" : 7532
                     },
                     "duration" : {
                        "text" : "23 mins",
                        "value" : 1366
                     },
                     "end_location" : {
                        "lat" : 44.4880918,
                        "lng" : -81.37978939999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSaugeen Rail Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kgdnGffwoNc@u@Uq@c@o@IKkAs@GAc@EYC?Am@TU@c@?c@@G?_A?a@?A?c@Ak@A[G{@O?AkBq@oAs@c@U{@m@_Aq@GEs@o@][]YmAeA[o@mAaAiAw@_BeAoA{@_BgAiBmA_Ao@}@o@_@Y_Aq@oA}@}AiA}AiA_@Y]W_@Y{C{B_@YeCkBkFgE[UCC]WoCqBeBqA_@Y]W}BcBqNqK_@W}AkAyDuC_@Y]W{EoD{C}B]W_@Y_@W{C}BsBaB_@Y]YuHaG]YyC_C_@YwD{C}@s@_As@}@m@u@g@s@]WMSKq@OMEw@QCA]Io@O}ASy@Kq@CcAEiAA_@?cCJqBXk@Na@JWH{Ab@kAd@MDa@PE@IBM@MA[CC?]EC?YAQBMDEFWh@K\\INKFOHE@]JIBWJa@Na@Na@Na@Na@NgC~@a@NeBn@cA^kDpAwK~DkE`Ba@NaExAeBp@gBn@wCfAgC~@gC`AkE~AyCfAgC~@iDnAgC~@gC`AmE~AqAd@YHWFe@RmBr@cA`@eBn@gCbAMDu@XcA^gC~@a@NeBn@y@tCa@xAa@vAMh@c@zAi@dBCH"
                     },
                     "start_location" : {
                        "lat" : 44.427581,
                        "lng" : -81.38868050000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 217
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 44.4897972,
                        "lng" : -81.3784852
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qapnGtnuoNMQECEEIAGCCAACEEGKq@a@cAq@_@W_C}A"
                     },
                     "start_location" : {
                        "lat" : 44.4880918,
                        "lng" : -81.37978939999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 832
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 146
                     },
                     "end_location" : {
                        "lat" : 44.496282,
                        "lng" : -81.3732651
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eGrosvenor St S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "glpnGpfuoN}AiAaFoDs@m@]Y{AqA]YyBkBkIaGeD_CwCwB"
                     },
                     "start_location" : {
                        "lat" : 44.4897972,
                        "lng" : -81.3784852
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 158
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 29
                     },
                     "end_location" : {
                        "lat" : 44.49559929999999,
                        "lng" : -81.3715191
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHigh St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wtqnG|etoNpBgHTu@"
                     },
                     "start_location" : {
                        "lat" : 44.496282,
                        "lng" : -81.3732651
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 979
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 243
                     },
                     "end_location" : {
                        "lat" : 44.50252829999999,
                        "lng" : -81.36436069999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eON-21 N\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "opqnG~zsoN_Ak@MMc@Yu@m@kDcCiDcCgDcCsB}AWS{@u@][_@Y]Y]Y}@w@cAy@s@cAGK]m@KOIOMU[k@M[Uy@CEMe@CGKe@ESCIKi@Im@"
                     },
                     "start_location" : {
                        "lat" : 44.49559929999999,
                        "lng" : -81.3715191
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1926
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 348
                     },
                     "end_location" : {
                        "lat" : 44.5181494,
                        "lng" : -81.3555049
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTurner St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBruce County Rd 13\u003c/b\u003e (signs for \u003cb\u003eBruse Rd 13\u003c/b\u003e)\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Bruce County Rd 13\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y{rnGfnroNoCF{EJoCDuDDq@?a@?SAUE]Iu@WMISK_@[gHsG{@w@uCkCmHwGWSQMsDgCaEoCaJ}FqD}Bm@_@aDmB_Ak@a@U}@k@a@M"
                     },
                     "start_location" : {
                        "lat" : 44.50252829999999,
                        "lng" : -81.36436069999999
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "7.4 km",
                  "value" : 7413
               },
               "duration" : {
                  "text" : "21 mins",
                  "value" : 1271
               },
               "end_address" : "935 Bruce County Rd 13, Sauble Beach, ON N0H 2G0, Canada",
               "end_location" : {
                  "lat" : 44.5706388,
                  "lng" : -81.3037025
               },
               "start_address" : "900a Bruce County Rd 13, Southampton, ON N0H 2L0, Canada",
               "start_location" : {
                  "lat" : 44.5181494,
                  "lng" : -81.3555049
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "7.4 km",
                        "value" : 7367
                     },
                     "duration" : {
                        "text" : "21 mins",
                        "value" : 1262
                     },
                     "end_location" : {
                        "lat" : 44.57082550000001,
                        "lng" : -81.3042207
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e on \u003cb\u003eBruce County Rd 13\u003c/b\u003e toward \u003cb\u003eCameron Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "m}unGzvpoNKCUGSEYC[CkDi@mAm@qAo@IGECa@U_Ak@aGoDaBaAsCcBoFgDy@c@_AYoA[gKyB_@IiB_@gB_@c@KgCi@mBa@s@Os@SWIcBw@oAy@y@k@{C{BA?yDuCSOeFsDy@w@{@}@s@eAYa@CE}BmDWa@_CoDuBcDc@o@Yc@_D{EmDoFaBaC}@iA{GyHyGyHiCuCu@y@_@g@IIa@q@s@qAo@sAWs@o@qBeAoDmB{GgBkGcAqDQk@Om@Su@wBkHa@wAsEyOm@aBYq@cAeBMM[_@i@m@e@_@s@c@m@USK_Cy@oHmCoEaByBy@_IwCA?_@Q[Oe@[k@k@gAqAs@}@_D_ECCkEwFgKoMwAkB}JkMgCcDY]ACe@g@s@q@}@q@}FuDCA[S{SuM"
                     },
                     "start_location" : {
                        "lat" : 44.5181494,
                        "lng" : -81.3555049
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "46 m",
                        "value" : 46
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 44.5706388,
                        "lng" : -81.3037025
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePashwood Dr\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uf`oGjvfoNd@gB"
                     },
                     "start_location" : {
                        "lat" : 44.57082550000001,
                        "lng" : -81.3042207
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "7.6 km",
                  "value" : 7564
               },
               "duration" : {
                  "text" : "23 mins",
                  "value" : 1404
               },
               "end_address" : "46 Shore Rd S, Sauble Beach, ON N0H 2G0, Canada",
               "end_location" : {
                  "lat" : 44.6294413,
                  "lng" : -81.2708686
               },
               "start_address" : "935 Bruce County Rd 13, Sauble Beach, ON N0H 2G0, Canada",
               "start_location" : {
                  "lat" : 44.5706388,
                  "lng" : -81.3037025
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "46 m",
                        "value" : 46
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 44.57082550000001,
                        "lng" : -81.3042207
                     },
                     "html_instructions" : "Head \u003cb\u003enorthwest\u003c/b\u003e on \u003cb\u003ePashwood Dr\u003c/b\u003e toward \u003cb\u003eBruce County Rd 13\u003c/b\u003e",
                     "polyline" : {
                        "points" : "oe`oGbsfoNe@fB"
                     },
                     "start_location" : {
                        "lat" : 44.5706388,
                        "lng" : -81.3037025
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 458
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 107
                     },
                     "end_location" : {
                        "lat" : 44.5738619,
                        "lng" : -81.30053160000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBruce County Rd 13\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uf`oGjvfoN{CkBwByAa@_@y@y@g@w@g@}@EGo@wA[y@Uw@Og@e@qA"
                     },
                     "start_location" : {
                        "lat" : 44.57082550000001,
                        "lng" : -81.3042207
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4.8 km",
                        "value" : 4783
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 865
                     },
                     "end_location" : {
                        "lat" : 44.61071,
                        "lng" : -81.27336740000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e2nd Ave S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sy`oGh_foNWPE@C?A?EAECIIEGU]CEWc@Wg@o@iAWe@We@q@aAm@{@IIYa@w@_ACCWY]]iAkAaBiBoBwB{@_A[]w@y@gAmACCi@g@i@c@g@WiDyA_FsBgCcAkBy@cBs@kA]oD}@_Dy@o@Mc@KkCm@uFoAkCm@WGa@KOCeAUa@Kc@K{Be@cAWeAWsFsAGIWa@S]Uk@{@iCy@_CGUIUQk@e@uASi@?AmAqDYw@_@}@mFaF][sCmCaDyC_@e@OUs@eAUg@?Ai@iAa@k@OSa@a@SSu@u@qCsCa@i@gAeBc@e@QQa@_@cA_AeBoA{A}@wBmAcAi@q@[m@a@uCiAUKwB_AcC_AWIOEy@Qo@MqBeAaFyAiF_BsAa@k@Qa@Ma@Ga@CYAs@DQAQAQEOEs@U"
                     },
                     "start_location" : {
                        "lat" : 44.5738619,
                        "lng" : -81.30053160000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "56 m",
                        "value" : 56
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 44.6107282,
                        "lng" : -81.27266019999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e16th St S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSilver Lake Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}_hoGpu`oNCmC"
                     },
                     "start_location" : {
                        "lat" : 44.61071,
                        "lng" : -81.27336740000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 2013
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 353
                     },
                     "end_location" : {
                        "lat" : 44.6286184,
                        "lng" : -81.2694836
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e2nd Ave S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "a`hoGbq`oN_Ey@uGwAcCg@OEuQuDsGgAq@@}@DcAF}AGiAGkL{AqAQmCMMAqGUiDOo@@yBE[?aBGyBE{BCuAC"
                     },
                     "start_location" : {
                        "lat" : 44.6107282,
                        "lng" : -81.27266019999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "80 m",
                        "value" : 80
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 44.6286035,
                        "lng" : -81.2704933
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e1st St S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{okoGf}_oNBhE"
                     },
                     "start_location" : {
                        "lat" : 44.6286184,
                        "lng" : -81.2694836
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "93 m",
                        "value" : 93
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 44.6294409,
                        "lng" : -81.270422
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLakeshore Blvd S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wokoGpc`oNkBG{@E"
                     },
                     "start_location" : {
                        "lat" : 44.6286035,
                        "lng" : -81.2704933
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "35 m",
                        "value" : 35
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 44.6294413,
                        "lng" : -81.2708686
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eShore Rd S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_ukoGbc`oN?h@?n@"
                     },
                     "start_location" : {
                        "lat" : 44.6294409,
                        "lng" : -81.270422
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "5.9 km",
                  "value" : 5914
               },
               "duration" : {
                  "text" : "20 mins",
                  "value" : 1188
               },
               "end_address" : "Sauble Falls Provincial Park, 1400 Sauble Falls Rd, Wiarton, ON N0H 2T0, Canada",
               "end_location" : {
                  "lat" : 44.67406159999999,
                  "lng" : -81.25677640000001
               },
               "start_address" : "46 Shore Rd S, Sauble Beach, ON N0H 2G0, Canada",
               "start_location" : {
                  "lat" : 44.6294413,
                  "lng" : -81.2708686
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "35 m",
                        "value" : 35
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 44.6294409,
                        "lng" : -81.270422
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eShore Rd S\u003c/b\u003e toward \u003cb\u003eLakeshore Blvd N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_ukoG|e`oN?o@?i@"
                     },
                     "start_location" : {
                        "lat" : 44.6294413,
                        "lng" : -81.2708686
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.5 km",
                        "value" : 3460
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 643
                     },
                     "end_location" : {
                        "lat" : 44.6599407,
                        "lng" : -81.275617
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLakeshore Blvd N\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_ukoGbc`oN{E?{BCuA?[?C?aCEeF@sB@gHDa@@uADgA?aA?c@?iC?eC?oLA{EFkFE}FAkKLc@?e@@kGNyANkDl@sHhAoATmBd@sCj@aA\\UFm@Z}ClAIDqExAyDvA}D|BoIdFSJc@Vi@To@Jg@DeB@"
                     },
                     "start_location" : {
                        "lat" : 44.6294409,
                        "lng" : -81.270422
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2305
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 444
                     },
                     "end_location" : {
                        "lat" : 44.6731136,
                        "lng" : -81.2573108
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSauble Falls Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ssqoGrcaoNOKKMIOIWE[QiCKcBa@eAqAkA_@_@KSq@kAk@_AIMo@kB]kBI_@Qo@c@Cu@Is@MuAYeAUe@Q{@i@cB}As@w@[c@e@m@GEc@a@WQkCi@oCq@EACAoAu@OIsEyCsEyCa@WIG_EmCsDiCCA{A{@OKKMKKKQk@iBS_AGm@?e@@k@LuJ@uA?EAk@Cs@?A]uFK}AKiBEq@"
                     },
                     "start_location" : {
                        "lat" : 44.6599407,
                        "lng" : -81.275617
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 114
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 94
                     },
                     "end_location" : {
                        "lat" : 44.67406159999999,
                        "lng" : -81.25677640000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eWalk your bicycle\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}etoGdq}nNMI_BcAGAgAY"
                     },
                     "start_location" : {
                        "lat" : 44.6731136,
                        "lng" : -81.2573108
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "mighGr`ziNyRbY}Nh^eD|OiF`D_KvNeAdHeBlUaBvBcEqD{EwRmIc]aO__@kYet@iFb@cDkBoDpC_^dkA{HdqAe@hUwQh^}G`Hwl@b]i\\rPin@rJec@bEkw@`p@uD|FuHvE_TyCav@oLsd@_Hk}@yMmqA{Roy@nKwR|@mCzNpCfTnCvXlBlViGrEig@cJwpAmLop@zHs^bOgSfHu\\NgPiCiM}BoEgIsRyKe\\oJ_XqHqHgJeJgNsi@cy@q\\qh@wBiDvBhDzGjKeCrDuLjQsHbLqP`We^ri@_sBf`DooB|yCqIpJuBpF_ClDmCZkQgXuOaVgJgNmIcMsAxEs@bC_@pAgApDkGhSkT|s@cOxf@k\\phAepAzhEyzBrjHex@liCaGrRyEnI{HtUcm@bqB__@noAqm@nrBgEvM@bGVxRaGeF}KvZ{Vhy@ss@j_C}HlWiBbG{EeDuV}PuXkR{F_EwC~AuB|EqUxPyOzIsc@vVyVpLqoAlu@oa@`t@ws@rcBwyClgH__BlvDiwCpaHm~D~nJmi@toAcf@pjAwNl]oHhQdAxLpBpVjCr]vC|_@dBbTgF`OsZ|e@yj@ziAqVrh@yVjOgs@djAc`@~h@qUba@oYhu@yQ~s@eJdf@mTde@{Zbe@wPr^i]xLe_@hMg`@n^wnAbs@il@jPyg@bJguAbWepA~Tqg@hKiHpGl@zIgE~FcHhE_DnBwEbFiWxe@iRroCoMzj@cd@bq@uaArxAeSlOqZtF{{@vOy}AdYkwCbj@yzAhXi`@pA{}@{Ugv@iSo^iGodBj`@yg@nO{VvIyKvQuk@zzAkPrLqVnI}ZjUsMrG_OdF_S~HkFtI{AdLoBfT~@li@bAft@}CpW}`@v~@eo@nvAoHfMqU`Q{cAbq@g`Axm@aStCwMcCgt@i[qe@gTix@oWke@qCqUhNyNzPoVfv@aQ|h@uJzLub@pYwk@j`@ca@xXc`@`f@k`AlqAk@rFgBcDyFi@{S}FseAix@}{A_hAeMeAqOzC}FtB_iBbq@iQtGoG~BcFnH{CpH{CqBkTcPcWeRx@wK_X{RwHkHeCkFmEaE}TD_\\yXuk@u]sw@k\\ef@oSej@gt@uZy^iNod@}O{f@oJ{F}_@_Ow^sd@w\\s]uSsQaECyCyBoCwDqBqF_BmAeLsPwNwO}YcNsk@_NyIwC_DsIeEcMc\\e_@yc@u[yc@{LgBc@cEgEyK_Ck\\aGiHA_g@gDsJQqAdEgDMiMCg]Jkn@Akj@|Dcs@hYyDiIwHkMcJgGgJkIui@gZ}B_c@{EcJ"
         },
         "summary" : "Waterloo Regional Rd 17 and Middlebrook Rd",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : [ 0, 1, 2, 3 ]
      }
   ],
   "status" : "OK"
}
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
