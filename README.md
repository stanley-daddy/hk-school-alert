# hk-school-alert
​Feature Summary: Real-Time Hong Kong School Status
​Core Objective
Automatically aggregate status feeds from HKO (Hong Kong Observatory) and EDB (Education Bureau) to deliver an instant, clear verdict on whether students need to attend school.
​App Decision Logic
​Class Suspension Triggered (Stay Home)
​HKO Signal: Typhoon Signal No. 8 or above / Red or Black Rainstorm Warning.  
​EDB Signal: Official class suspension order issued.  
​Target Group: All day schools, primary, secondary, and kindergartens.  
​Partial Suspension Triggered
​HKO Signal: Typhoon Signal No. 3.  
​Target Group: Kindergartens and Special Needs schools suspended; primary/secondary operate as normal.  
​Normal Operations (Go to School)
​HKO Signal: Standby Signal No. 1, Amber Rainstorm Warning, or No Signal.  
​Target Group: All schools open as usual.  
