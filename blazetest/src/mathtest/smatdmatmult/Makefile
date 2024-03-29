#==================================================================================================
#
#  Makefile for the smatdmatmult module of the Blaze test suite
#
#  Copyright (C) 2013 Klaus Iglberger - All Rights Reserved - All Rights Reserved
#
#  This file is part of the Blaze library. You can redistribute it and/or modify it under
#  the terms of the New (Revised) BSD License. Redistribution and use in source and binary
#  forms, with or without modification, are permitted provided that the following conditions
#  are met:
#
#  1. Redistributions of source code must retain the above copyright notice, this list of
#     conditions and the following disclaimer.
#  2. Redistributions in binary form must reproduce the above copyright notice, this list
#     of conditions and the following disclaimer in the documentation and/or other materials
#     provided with the distribution.
#  3. Neither the names of the Blaze development group nor the names of its contributors
#     may be used to endorse or promote products derived from this software without specific
#     prior written permission.
#
#  THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY
#  EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
#  OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT
#  SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
#  INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
#  TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
#  BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
#  CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
#  ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH
#  DAMAGE.
#
#==================================================================================================


# Including the compiler and library settings
ifneq ($(MAKECMDGOALS),clean)
-include ../../Makeconfig
endif


# Setting the source, object and dependency files
SRC = $(wildcard ./*.cpp)
DEP = $(SRC:.cpp=.d)
OBJ = $(SRC:.cpp=.o)
BIN = $(SRC:.cpp=)


# General rules
default: MCaM3x3a MCaM3x3b MCbM3x3a MCbM3x3b \
         MCaMHa MCaMHb MCbMHa MCbMHb \
         MCaMDa MCaMDb MCbMDa MCbMDb \
         SCaSDa SCaSDb SCbSDa SCbSDb \
         LCaLDa LCaLDb LCbLDa LCbLDb \
         UCaUDa UCaUDb UCbUDa UCbUDb \
         DCaDDa DCaDDb DCbDDa DCbDDb \
         AliasingTest
all: $(BIN)
essential: MCaM3x3a MCaMHa MCaMDa SCaSDa LCaLDa UCaUDa DCaDDa AliasingTest
single: MCaMDa


# Build rules
DCaD3x3a: DCaD3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaD3x3b: DCaD3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaDDa: DCaDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaDDb: DCaDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaDHa: DCaDHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaDHb: DCaDHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaLDa: DCaLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaLDb: DCaLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaMDa: DCaMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaMDb: DCaMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaSDa: DCaSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaSDb: DCaSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaSLDa: DCaSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaSLDb: DCaSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaSUDa: DCaSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaSUDb: DCaSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaUDa: DCaUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCaUDb: DCaUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

DCbD3x3a: DCbD3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbD3x3b: DCbD3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbDDa: DCbDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbDDb: DCbDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbDHa: DCbDHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbDHb: DCbDHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbLDa: DCbLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbLDb: DCbLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbMDa: DCbMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbMDb: DCbMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbSDa: DCbSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbSDb: DCbSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbSLDa: DCbSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbSLDb: DCbSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbSUDa: DCbSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbSUDb: DCbSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbUDa: DCbUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
DCbUDb: DCbUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

LCaDDa: LCaDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaDDb: LCaDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaL3x3a: LCaL3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaL3x3b: LCaL3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaLDa: LCaLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaLDb: LCaLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaLHa: LCaLHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaLHb: LCaLHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaMDa: LCaMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaMDb: LCaMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaSDa: LCaSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaSDb: LCaSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaSLDa: LCaSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaSLDb: LCaSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaSUDa: LCaSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaSUDb: LCaSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaUDa: LCaUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCaUDb: LCaUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

LCbDDa: LCbDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbDDb: LCbDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbL3x3a: LCbL3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbL3x3b: LCbL3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbLDa: LCbLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbLDb: LCbLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbLHa: LCbLHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbLHb: LCbLHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbMDa: LCbMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbMDb: LCbMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbSDa: LCbSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbSDb: LCbSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbSLDa: LCbSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbSLDb: LCbSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbSUDa: LCbSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbSUDb: LCbSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbUDa: LCbUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
LCbUDb: LCbUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

MCaDDa: MCaDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaDDb: MCaDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaLDa: MCaLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaLDb: MCaLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM2x2a: MCaM2x2a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM2x2b: MCaM2x2b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM3x3a: MCaM3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM3x3b: MCaM3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM4x4a: MCaM4x4a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM4x4b: MCaM4x4b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM5x5a: MCaM5x5a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM5x5b: MCaM5x5b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM6x6a: MCaM6x6a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM6x6b: MCaM6x6b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM7x13a: MCaM7x13a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM7x13b: MCaM7x13b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM16x8a: MCaM16x8a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaM16x8b: MCaM16x8b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaMDa: MCaMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaMDb: MCaMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaMHa: MCaMHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaMHb: MCaMHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaSDa: MCaSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaSDb: MCaSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaSLDa: MCaSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaSLDb: MCaSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaSUDa: MCaSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaSUDb: MCaSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaUDa: MCaUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCaUDb: MCaUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

MCbDDa: MCbDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbDDb: MCbDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbLDa: MCbLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbLDb: MCbLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM2x2a: MCbM2x2a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM2x2b: MCbM2x2b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM3x3a: MCbM3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM3x3b: MCbM3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM4x4a: MCbM4x4a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM4x4b: MCbM4x4b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM5x5a: MCbM5x5a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM5x5b: MCbM5x5b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM6x6a: MCbM6x6a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM6x6b: MCbM6x6b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM7x13a: MCbM7x13a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM7x13b: MCbM7x13b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM16x8a: MCbM16x8a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbM16x8b: MCbM16x8b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbMDa: MCbMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbMDb: MCbMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbMHa: MCbMHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbMHb: MCbMHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbSDa: MCbSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbSDb: MCbSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbSLDa: MCbSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbSLDb: MCbSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbSUDa: MCbSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbSUDb: MCbSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbUDa: MCbUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
MCbUDb: MCbUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

SCaDDa: SCaDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaDDb: SCaDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaLDa: SCaLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaLDb: SCaLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaMDa: SCaMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaMDb: SCaMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaS3x3a: SCaS3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaS3x3b: SCaS3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSDa: SCaSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSDb: SCaSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSHa: SCaSHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSHb: SCaSHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSLDa: SCaSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSLDb: SCaSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSUDa: SCaSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaSUDb: SCaSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaUDa: SCaUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCaUDb: SCaUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

SCbDDa: SCbDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbDDb: SCbDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbLDa: SCbLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbLDb: SCbLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbMDa: SCbMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbMDb: SCbMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbS3x3a: SCbS3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbS3x3b: SCbS3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSDa: SCbSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSDb: SCbSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSHa: SCbSHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSHb: SCbSHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSLDa: SCbSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSLDb: SCbSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSUDa: SCbSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbSUDb: SCbSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbUDa: SCbUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
SCbUDb: SCbUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

UCaDDa: UCaDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaDDb: UCaDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaLDa: UCaLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaLDb: UCaLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaMDa: UCaMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaMDb: UCaMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaSDa: UCaSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaSDb: UCaSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaSLDa: UCaSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaSLDb: UCaSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaSUDa: UCaSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaSUDb: UCaSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaU3x3a: UCaU3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaU3x3b: UCaU3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaUDa: UCaUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaUDb: UCaUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaUHa: UCaUHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCaUHb: UCaUHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

UCbDDa: UCbDDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbDDb: UCbDDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbLDa: UCbLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbLDb: UCbLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbMDa: UCbMDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbMDb: UCbMDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbSDa: UCbSDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbSDb: UCbSDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbSLDa: UCbSLDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbSLDb: UCbSLDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbSUDa: UCbSUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbSUDb: UCbSUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbU3x3a: UCbU3x3a.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbU3x3b: UCbU3x3b.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbUDa: UCbUDa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbUDb: UCbUDb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbUHa: UCbUHa.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)
UCbUHb: UCbUHb.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)

AliasingTest: AliasingTest.o
	@$(CXX) $(CXXFLAGS) -o $@ $< $(LIBRARIES)


# Cleanup
clean:
	@$(RM) $(DEP) $(OBJ) $(BIN)


# Makefile includes
ifneq ($(MAKECMDGOALS),clean)
-include $(DEP)
endif


# Makefile generation
%.d: %.cpp
	@$(CXX) -MM -MP -MT "$*.o $*.d" -MF $@ $(CXXFLAGS) $<


# Setting the independent commands
.PHONY: default all essential single clean
