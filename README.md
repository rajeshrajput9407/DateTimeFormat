# DateTimeFormat
Date Time Format 
 
            var systemDate = DateTime.Now;
            var systemDate2 = DateTime.UtcNow;
            var Locatime =  systemDate2.ToLocalTime();
            string localTime = TimeZone.CurrentTimeZone.ToLocalTime(systemDate2).ToString("MM-dd-yyyy hh:mm tt");
          
