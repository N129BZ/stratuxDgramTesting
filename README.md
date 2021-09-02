# Parse Stratux UDP port 4000 AHRS messages 
This node app parses Stratux AHRS UDP messages on port 4000. This implementation uses the Kaitai struct compiler to generate javascript code to parse the incoming byte array.

###
   At run time, requires a reference to KaitaiStream, which is installed as part of the Kaitai struct compiler. The compiler generates your preferred language from the ahrs.ksy yaml file. 
   ```
   Samples: 
       
       ksc -t javascript ahrs.ksy
       ksc -t python ahrs.ksy
   ```
###
   https://github.com/kaitai-io/kaitai_struct_compiler/releases
