## How to use the iCUE Growth Services API
1. Apply for user token (https://www.i-cue.solutions/icue-home/contact_us)
2. Get your data ready 
(check here what to look out for when setting up your planning levels https://www.i-cue.solutions/icue-home/icue-growth-services/integrated-business-planning-and-portfolio-management)
3. Select the endpoint
4. Enter your TOKEN
5. Fill in the JSON body
6. Go


### Example
#### Portfolio 
https://api.i-cue.solutions/portfolio/abc

    TOKEN

```   
    {
        "planningLevelId": "PlanningLevel_XXX2T5",
        "startDate": "1/1/2018",
        "method": "AutoBestPick",
        "data": [
          {
            "timeSeriesId": "P1-D",
            "historyValues": [
              8594415,
              7627771,
              7363551,
              9173250,
              8528521,
              6719701,
              9310787,
              8594079,
              8785323,
              8089000,
              7409652,
              7054603,
              10284810,
              8365926,
              8539196,
              9916603,
              8542274,
              7644600,
              10036527,
              9295158,
              9201934,
              8430721,
              7702605,
              7444809,
              10108721,
                        7784572,
                        8917040,
                        9220340,
                        7784217,
                        7233855,
                        9381536,
                        8300919,
                        8433277,
                        7752865,
                        7051850,
                        6831220
                      ]
                    },
                    {
                      "timeSeriesId": "P2-D",
                      "historyValues": [
                        210105,
                        182154,
                        174397,
                        208943,
                        184592,
                        123576,
                        157089,
                        166230,
                        162602,
                        104583,
                        114663,
                        171866,
                        222451,
                        181190,
                        230876,
                        262776,
                        274761,
                        202587,
                        282945,
                        250465,
                        233694,
                        215853,
                        179321,
                        201217,
                        319231,
                        228012,
                        243056,
                        301447,
                        204204,
                        293140,
                        231815,
                        202636,
                        232653,
                        165724,
                        189780,
                        184601
                      ]
                    },
                    {
                      "timeSeriesId": "P3-D",
                      "historyValues": [
                        20049,
                        17468,
                        11022,
                        2726,
                        13898,
                        30359,
                        41517,
                        14520,
                        32496,
                        7179,
                        68541,
                        58858,
                        16039,
                        24181,
                        25574,
                        29744,
                        24756,
                        96453,
                        65186,
                        78565,
                        61661,
                        82438,
                        57538,
                        97371,
                        112443,
                        66943,
                        89542,
                        106921,
                        79249,
                        122105,
                        91325,
                        84837,
                        91796,
                        109078,
                        67343,
                        118503
                      ]
                    },
                    {
                      "timeSeriesId": "P4-D",
                      "historyValues": [
                        6293,
                        8199,
                        8135,
                        9591,
                        7108,
                        7183,
                        9305,
                        10827,
                        7412,
                        5912,
                        7738,
                        7342,
                        6673,
                        10832,
                        9530,
                        11494,
                        6681,
                        10757,
                        7391,
                        9298,
                        10173,
                        14275,
                        12524,
                        13567,
                        14393,
                        11706,
                        15098,
                        14510,
                        13156,
                        14694,
                        21786,
                        18030,
                        19499,
                        13861,
                        23509,
                        24672
                      ]
                    },
                    {
                      "timeSeriesId": "P5-D",
                      "historyValues": [
                        16044,
                        466,
                        15941,
                        21222,
                        9960,
                        16958,
                        1202,
                        7470,
                        641,
                        17071,
                        2925,
                        6014,
                        495,
                        5490,
                        2498,
                        297,
                        0,
                        30581,
                        4592,
                        7246,
                        17741,
                        565,
                        0,
                        0,
                        0,
                        3998,
                        27988,
                        4676,
                        16895,
                        5474,
                        0,
                        22743,
                        13143,
                        3557,
                        0,
                        13848
                      ]
                    }
                  ]
                }


### Please note
Use the same data for the Insight-Drive Planning endpoints. 
**Make sure to change method to icueMLO or icueMLP when using the AI based forecasting.** 
