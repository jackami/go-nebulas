add_library(nbre_core
  ir_warden.cpp
  exception_handler.cpp
  neb_ipc/server/ipc_callback_holder.cpp
  neb_ipc/client/ipc_client_endpoint.cpp
  neb_ipc/server/ipc_server_endpoint.cpp
  neb_ipc/ipc_interface.cpp
)
#enable_clang_tidy(nbre_core)
