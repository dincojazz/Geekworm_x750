# Geekworm_x750
Home Assistant Geekworm x750 Addon based on Home Assistant Geekworm x720 Addon from user Beduir https://github.com/Beduir/x720.git

Change fixes:
   - Fixed deprecated async_add_job with async_add_executor_job

Сompatibility:
   - Geekworm x750
   - Geekworm x720

configuration.yaml:

	sensor:
  	  - platform: x750
	    name: 'RPi Battery'
