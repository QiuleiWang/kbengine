LIB =	helper

SRCS =				\
	debug_helper		\
	debug_option		\
	profile			\
	profiler		\
	script_loglevel		\
	sys_info		\
	watcher

ifndef KBE_ROOT
export KBE_ROOT := $(subst /kbe/src/lib/$(LIB),,$(CURDIR))
endif

ifndef NO_USE_LOG4CXX
	NO_USE_LOG4CXX = 0
	CPPFLAGS += -DLOG4CXX_STATIC
endif

include $(KBE_ROOT)/kbe/src/build/common.mak