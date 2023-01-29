idf_component_register(SRCS "src/PS4Controller.cpp" "src/PS4Controller.h" "src/ps4.c" "src/ps4.h" "src/ps4_int.h" "src/ps4_l2cap.c"  "src/ps4_parser.c" "src/ps4_spp.c" "src/osi/allocator.h" "src/stack/bt_types.h" "src/stack/btm_api.h" "src/stack/gap_api.h" "src/stack/hcidefs.h" "src/stack/l2c_api.h" "src/stack/l2cdefs.h"
                       INCLUDE_DIRS "src"
					   REQUIRES bt 
				   )
# target_compile_options(${COMPONENT_LIB} PRIVATE -std=gnu++20)
