# es3read
Bash script to read PV and battery voltes using UDP with CouldBoxM1 connected to eSmart3


  Make sure after you receive 2nd reply to set correct sequence for 3rd packet as in example below, later it will keep the seq   for this host.

  Request: '230000001601fa4c9b5fe88f559834b67200aee471e7a4dc000064'

  Reply: '2800000011000140d63c04366f000000000002010200' - seq number is 0102 so next query will look like:

  Get details:: '830000000f010289af00aa010001000300001e33' - notice 0102.
