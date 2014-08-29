
all:
EXTRA_CXXFLAGS = -Wno-sign-compare
include ../kaldi.mk

LDFLAGS += $(CUDA_LDFLAGS)
LDLIBS += $(CUDA_LDLIBS)

BINFILES = svm-predict svm-scale svm-train

OBJFILES =



TESTFILES =

ADDLIBS = ../libsvm.a

include ../makefiles/default_rules.mk
