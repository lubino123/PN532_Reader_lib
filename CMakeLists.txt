set(COMPONENT_ADD_INCLUDEDIRS .)
set(COMPONENT_SRCS "NFC_reader.c")
idf_component_register(SRCS "NFC_reader.c"
                       SRCS "NFC_reader.c"
                       INCLUDE_DIRS "."
                       INCLUDE_DIRS "."
                       REQUIRES "driver"
                       REQUIRES "pn532")
