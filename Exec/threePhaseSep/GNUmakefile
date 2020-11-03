#AMREX_HOME defines the directory in which we will find the BoxLib directory
AMREX_HOME ?= ../../../amrex
HYPRE_DIR=../../../hypre/src/hypre
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
USE_EB = FALSE

USE_VELOCITY = FALSE
USE_HYPRE = TRUE
EBASE = amr

Bpack   := ./Make.package
Blocs   := .

include $(TOP)/Exec/Make.IAMR
