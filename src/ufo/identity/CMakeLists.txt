# (C) Copyright 2017-2018 UCAR.
#
# This software is licensed under the terms of the Apache Licence Version 2.0
# which can be obtained at http://www.apache.org/licenses/LICENSE-2.0.

set ( identity_files
    ObsIdentity.h
    ObsIdentity.cc
    ObsIdentityTLAD.h
    ObsIdentityTLAD.cc
    ObsIdentity.interface.F90
    ObsIdentity.interface.h
    ObsIdentityTLAD.interface.F90
    ObsIdentityTLAD.interface.h
    ufo_identity_mod.F90
    ufo_identity_tlad_mod.F90
)

PREPEND( _p_identity_files       "identity"       ${identity_files} )

set ( identity_src_files
      ${_p_identity_files}
      PARENT_SCOPE
)

