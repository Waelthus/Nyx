# AMREX_HOME defines the directory in which we will find all the BoxLib code
AMREX_HOME ?= ../../../amrex

# TOP defines the directory in which we will find Source, Exec, etc
TOP = ../..

# compilation options
COMP    = gcc

# NOTE THAT THIS CODE IS NOT THREAD-SAFE RIGHT NOW -- DO NOT RUN WITH USE_OMP
USE_MPI = TRUE
USE_OMP = TRUE

PRECISION = DOUBLE
DEBUG     = FALSE

# physics
DIM      = 3
USE_GRAV = FALSE

USE_HEATCOOL = FALSE

USE_FORCING = TRUE

USE_SDC = FALSE

#USE_CGS = TRUE

Bpack := ./Make.package
Blocs := .

include $(TOP)/Exec/Make.Nyx

