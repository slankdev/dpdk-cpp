

prefix = ..

TARGET = a.out
SRCS   = main.cc

OBJS   = $(SRCS:.cc=.o)


all: $(TARGET)

clean:
	$(RM) $(TARGET) $(OBJS)

re: clean all


include $(prefix)/mk/vars.mk
LDFLAGS += -lslankdev

