#
# Makefile for ABINIT                                      -*- Automake -*-
# Generated by make-makefiles-corelibs on 2012/04/11 04:16:05 +0000

#
# IMPORTANT NOTE
#
# Any manual change to this file will systematically be overwritten.
# Please modify the make-makefiles-corelibs script or its config file instead.
#

AM_CFLAGS = @ABI_CPPFLAGS@
AM_FCFLAGS = @FPPFLAGS@ @FCFLAGS_FREEFORM@ @FCFLAGS_MODDIR@ @fcflags_opt_79_seqpar_mpi@

INCLUDES = \
	@src_incs_incs@ \
	@fallbacks_incs@ \
	@lib_bigdft_incs@ \
	@lib_etsf_io_incs@ \
	@lib_netcdf_incs@

# Regular source files
lib79_seqpar_mpi_srcs = \
	inwffil.F90 \
	lobpcgccIIwf.F90 \
	lobpcgccIIIwf.F90 \
	lobpcgwf.F90 \
	lobpcgIIwf.F90 \
	mv_3dte.F90 \
	m_lobpcg.F90 \
	m_lobpcgIIIwf.F90 \
	subdiago.F90 \
	tddft.F90 \
	vtowfk.F90 \
	vtorho.F90 \
	wfsinp.F90 \
	wvl_wfsinp_disk.F90 \
	wvl_wfsinp_reformat.F90 \
	wvl_wfsinp_scratch.F90 \
	wvl_vtorho.F90 \
	interfaces_79_seqpar_mpi.F90

# Library description
noinst_LIBRARIES = lib79_seqpar_mpi.a

lib79_seqpar_mpi_a_SOURCES= $(lib79_seqpar_mpi_srcs)

CLEANFILES = \
	inwffil_cpp.f90 \
	lobpcgccIIwf_cpp.f90 \
	lobpcgccIIIwf_cpp.f90 \
	lobpcgwf_cpp.f90 \
	lobpcgIIwf_cpp.f90 \
	mv_3dte_cpp.f90 \
	m_lobpcg_cpp.f90 \
	m_lobpcgIIIwf_cpp.f90 \
	subdiago_cpp.f90 \
	tddft_cpp.f90 \
	vtowfk_cpp.f90 \
	vtorho_cpp.f90 \
	wfsinp_cpp.f90 \
	wvl_wfsinp_disk_cpp.f90 \
	wvl_wfsinp_reformat_cpp.f90 \
	wvl_wfsinp_scratch_cpp.f90 \
	wvl_vtorho_cpp.f90 \
	interfaces_79_seqpar_mpi_cpp.f90

EXTRA_DIST = abinit.src

EXTRA_DIST += abinit.dep

#Dependencies (inside the directory) of the directory ./src/79_seqpar_mpi
#
#COPYRIGHT
#Copyright (C) 2010-2011 ABINIT group
#This file is distributed under the terms of the
#GNU General Public License, see ~abinit/COPYING
#or http://www.gnu.org/copyleft/gpl.txt .
#
#THIS FILE IS GENERATED AUTOMATICALLY BY abilint.
#To do that: config/scripts/abilint --dependencies . .

CLEANFILES += \
	interfaces_79_seqpar_mpi.$(MODEXT) \
	m_lobpcg.$(MODEXT) 

inwffil.$(OBJEXT): interfaces_79_seqpar_mpi.$(OBJEXT) 

lobpcgIIwf.$(OBJEXT): interfaces_79_seqpar_mpi.$(OBJEXT) 

lobpcgccIIwf.$(OBJEXT): interfaces_79_seqpar_mpi.$(OBJEXT) 

lobpcgwf.$(OBJEXT): m_lobpcg.$(OBJEXT) 

m_lobpcgIIIwf.$(OBJEXT): interfaces_79_seqpar_mpi.$(OBJEXT) 

vtorho.$(OBJEXT): interfaces_79_seqpar_mpi.$(OBJEXT) 

vtowfk.$(OBJEXT): interfaces_79_seqpar_mpi.$(OBJEXT) 

EXTRA_DIST += _79_seqpar_mpi_
