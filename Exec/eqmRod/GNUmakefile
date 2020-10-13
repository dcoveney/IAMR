#AMREX_HOME defines the directory in which we will find the BoxLib directory
AMREX_HOME ?= ../../../Documents/amrex
HYPRE_DIR=../../../../hypre-18.2.2
#TOP defines the directory in which we will find Source, Exec, etc.
TOP = ../..

#
# Variables for the user to set ...
#

PRECISION   = DOUBLE

DIM         = 2
COMP        = gnu

DEBUG       = FALSE
USE_MPI     = TRUE
USE_OMP     = FALSE
PROFILE     = FALSE
ENABLE_HYPRE = ON


USE_CUDA = FALSE
USE_HYPRE = FALSE
USE_EB = FALSE

EBASE = amr

Bpack   := ./Make.package
Blocs   := .

include $(TOP)/Exec/Make.IAMR
