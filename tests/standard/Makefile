# echidna - IEC 61131-3 compiler and virtual machine

LIBS_SUBDIR:= arithmetic bistable bitstring bitwise comparison counters edge numeric rtc select string time timers type
.PHONY: $(LIBS_SUBDIR)

all: clean
	for SUBDIR in $(LIBS_SUBDIR); do make -C $$SUBDIR ; done

clean:
	for SUBDIR in $(LIBS_SUBDIR); do make -C $$SUBDIR $@ ; done

