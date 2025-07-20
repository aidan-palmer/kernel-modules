obj-m += hello_kernel.o

all:
	${MAKE} -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
