idf_component_register(SRCS "src/PS4Controller.h" "src/ps4.h" "src/ps4.c" "src/ps4_int.h" "src/ps4_l2cap.c"  "src/ps4_parser.c" "src/ps4_spp.c" "src/stack/l2c_api.h"
                       INCLUDE_DIRS "src/osi" "src/stack"
					   REQUIRES bt 
				   )
