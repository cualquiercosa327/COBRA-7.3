
clean:
	rm -f *DEBUG *.o *.elf *.self *.476 *.bin *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o

all:
	rm -f *.o *.elf *.self *.476 *.bin *.476c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476C --no-print-directory

	rm -f *.o *.elf *.476 *.bin *.476d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476D --no-print-directory

	rm -f *.o *.elf *.476 *.bin *.476c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476C_dbg --no-print-directory

	rm -f *.o *.elf *.476 *.bin *.476d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476D_dbg --no-print-directory

	rm -f *.o *.elf  *.476 *.bin *.476c *.476d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o

dbg:
	rm -f *.o *.elf *.self *.476 *.bin *.476c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476C_dbg --no-print-directory

	rm -f *.o *.elf *.476 *.bin *.476d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476D_dbg --no-print-directory

	rm -f *.o *.elf  *.476 *.bin *.476c *.476d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o

re:
	rm -f *.o *.elf *.self *.476 *.bin *.476c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476C --no-print-directory

	rm -f *.o *.elf *.476 *.bin *.476d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_476D --no-print-directory

	rm -f *.o *.elf  *.476 *.bin *.476c *.476d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
