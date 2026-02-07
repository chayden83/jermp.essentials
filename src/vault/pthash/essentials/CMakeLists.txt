vault_add_header_only_library(vault.pthash.essentials)

target_sources(vault.pthash.essentials PUBLIC FILE_SET HEADERS BASE_DIRS ${PROJECT_SOURCE_DIR}/include FILES
  ${PROJECT_SOURCE_DIR}/include/vault/pthash/essentials
)

vault_install_targets(
  TARGETS vault.pthash.essentials
)

vault_install_export()
