################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include serial/EFR32/subdir.mk
-include serial/subdir.mk
-include nvm3/EFR32/subdir.mk
-include nvm3/subdir.mk
-include mbedtls/EFR32_2_2/subdir.mk
-include mbedtls/EFR32/subdir.mk
-include led/EFR32/subdir.mk
-include hal-library/EFR32/subdir.mk
-include gpd-components/subdir.mk
-include emlib/subdir.mk
-include emdrv/subdir.mk
-include ember-minimal-printf/subdir.mk
-include command-interpreter2/subdir.mk
-include coexistence-stub/EFR32/subdir.mk
-include cli/subdir.mk
-include ccm-encryption/subdir.mk
-include button/EFR32/subdir.mk
-include apps/subdir.mk
-include antenna-stub/subdir.mk
-include adc/EFR32/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: pre-build main-build

# Main-build Target
main-build: gpd_sensor_mg22_v673.axf

# Tool invocations
gpd_sensor_mg22_v673.axf: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: GNU ARM C Linker'
	arm-none-eabi-gcc -g3 -gdwarf-2 -mcpu=cortex-m33 -mthumb -T "C:/SiliconLabs/SimplicityStudio/v4_2/developer/sdks/gecko_sdk_suite/v2.7//platform/base/hal/micro/cortexm3/efm32/gcc-cfg.ld" -L"C:/SiliconLabs/SimplicityStudio/v4_2/developer/sdks/gecko_sdk_suite/v2.7//platform/base/hal/micro/cortexm3/" -Xlinker --defsym=FLASH_SIZE=524288 -Xlinker --defsym=RAM_SIZE=32768 -Xlinker --defsym=FLASH_PAGE_SIZE=8192 -Xlinker --defsym=SIMEEPROM_SIZE=32768 -Xlinker --defsym=PSSTORE_SIZE=0 -Xlinker --defsym=LONGTOKEN_SIZE=0 -Xlinker --defsym=HEADER_SIZE=512 -Xlinker --defsym=BTL_SIZE=24576 -Xlinker --defsym=LOCKBITS_IN_MAINFLASH_SIZE=8192 -Xlinker --defsym=NULL_BTL=1 -Xlinker --defsym=EMBER_MALLOC_HEAP_SIZE=0 -Xlinker --gc-sections -Xlinker -Map="gpd_sensor_mg22_v673.map" -mfpu=fpv5-sp-d16 -mfloat-abi=hard --specs=nano.specs -o gpd_sensor_mg22_v673.axf -Wl,--start-group "./adc/EFR32/adc-efr32.o" "./antenna-stub/antenna-stub.o" "./apps/gpd-apps-commission.o" "./apps/gpd-apps-crypto-test.o" "./apps/gpd-apps-main.o" "./apps/gpd-apps-node.o" "./apps/gpd-apps-utility.o" "./button/EFR32/button.o" "./ccm-encryption/ccm-star.o" "./ccm-encryption/em_crypto.o" "./cli/gpd-cli.o" "./coexistence-stub/EFR32/coexistence-802154.o" "./coexistence-stub/EFR32/coulomb-counter-802154.o" "./command-interpreter2/command-interpreter2.o" "./ember-minimal-printf/ember-printf.o" "./emdrv/dmadrv.o" "./emdrv/gpiointerrupt.o" "./emdrv/sl_sleeptimer.o" "./emdrv/sl_sleeptimer_hal_rtcc.o" "./emdrv/sleep.o" "./emdrv/tempdrv.o" "./emdrv/uartdrv.o" "./emdrv/ustimer.o" "./emlib/em_adc.o" "./emlib/em_cmu.o" "./emlib/em_core.o" "./emlib/em_emu.o" "./emlib/em_eusart.o" "./emlib/em_gpio.o" "./emlib/em_i2c.o" "./emlib/em_ldma.o" "./emlib/em_leuart.o" "./emlib/em_msc.o" "./emlib/em_prs.o" "./emlib/em_rmu.o" "./emlib/em_rtcc.o" "./emlib/em_se.o" "./emlib/em_system.o" "./emlib/em_timer.o" "./emlib/em_usart.o" "./emlib/em_wdog.o" "./emlib/system_efr32mg22.o" "./gpd-bookkeeping.o" "./gpd-callback-stubs.o" "./gpd-callbacks.o" "./gpd-cli.o" "./gpd-events.o" "./gpd-components/gpd-nv.o" "./gpd-components/gpd-nwk.o" "./gpd-components/gpd-rail.o" "./gpd-components/gpd-security.o" "./gpd-components/gpd-send-receive.o" "./hal-library/EFR32/assert-crash-handlers.o" "./hal-library/EFR32/crc.o" "./hal-library/EFR32/cstartup-common.o" "./hal-library/EFR32/endian.o" "./hal-library/EFR32/faults-v7m.o" "./hal-library/EFR32/hal-config-gpio.o" "./hal-library/EFR32/hal-config.o" "./hal-library/EFR32/isr-stubs.o" "./hal-library/EFR32/long-token.o" "./hal-library/EFR32/mem-util.o" "./hal-library/EFR32/mfg-token.o" "./hal-library/EFR32/micro-common.o" "./hal-library/EFR32/micro.o" "./hal-library/EFR32/random.o" "./hal-library/EFR32/sl_mpu.o" "./hal-library/EFR32/sleep-efm32.o" "./hal-library/EFR32/token-def.o" "./hal-library/EFR32/token.o" "./led/EFR32/led.o" "./mbedtls/EFR32/aes.o" "./mbedtls/EFR32/aes_aes.o" "./mbedtls/EFR32/aesni.o" "./mbedtls/EFR32/arc4.o" "./mbedtls/EFR32/asn1parse.o" "./mbedtls/EFR32/asn1write.o" "./mbedtls/EFR32/base64.o" "./mbedtls/EFR32/bignum.o" "./mbedtls/EFR32/blowfish.o" "./mbedtls/EFR32/camellia.o" "./mbedtls/EFR32/ccm.o" "./mbedtls/EFR32/certs.o" "./mbedtls/EFR32/cipher.o" "./mbedtls/EFR32/cipher_wrap.o" "./mbedtls/EFR32/cmac.o" "./mbedtls/EFR32/crypto_aes.o" "./mbedtls/EFR32/crypto_ble.o" "./mbedtls/EFR32/crypto_ecp.o" "./mbedtls/EFR32/crypto_management.o" "./mbedtls/EFR32/crypto_sha.o" "./mbedtls/EFR32/cryptoacc_aes.o" "./mbedtls/EFR32/cryptoacc_ccm.o" "./mbedtls/EFR32/cryptoacc_cmac.o" "./mbedtls/EFR32/cryptoacc_ecp.o" "./mbedtls/EFR32/cryptoacc_gcm.o" "./mbedtls/EFR32/cryptoacc_management.o" "./mbedtls/EFR32/cryptoacc_sha.o" "./mbedtls/EFR32/cryptoacc_trng.o" "./mbedtls/EFR32/ctr_drbg.o" "./mbedtls/EFR32/debug.o" "./mbedtls/EFR32/des.o" "./mbedtls/EFR32/dhm.o" "./mbedtls/EFR32/ecdh.o" "./mbedtls/EFR32/ecdsa.o" "./mbedtls/EFR32/ecjpake.o" "./mbedtls/EFR32/ecp.o" "./mbedtls/EFR32/ecp_curves.o" "./mbedtls/EFR32/entropy.o" "./mbedtls/EFR32/entropy_adc.o" "./mbedtls/EFR32/entropy_poll.o" "./mbedtls/EFR32/entropy_rail.o" "./mbedtls/EFR32/error.o" "./mbedtls/EFR32/gcm.o" "./mbedtls/EFR32/havege.o" "./mbedtls/EFR32/hmac_drbg.o" "./mbedtls/EFR32/md.o" "./mbedtls/EFR32/md2.o" "./mbedtls/EFR32/md4.o" "./mbedtls/EFR32/md5.o" "./mbedtls/EFR32/md_wrap.o" "./mbedtls/EFR32/memory_buffer_alloc.o" "./mbedtls/EFR32/net_sockets.o" "./mbedtls/EFR32/oid.o" "./mbedtls/EFR32/padlock.o" "./mbedtls/EFR32/pem.o" "./mbedtls/EFR32/pk.o" "./mbedtls/EFR32/pk_wrap.o" "./mbedtls/EFR32/pkcs11.o" "./mbedtls/EFR32/pkcs12.o" "./mbedtls/EFR32/pkcs5.o" "./mbedtls/EFR32/pkparse.o" "./mbedtls/EFR32/pkwrite.o" "./mbedtls/EFR32/radioaes.o" "./mbedtls/EFR32/radioaes_aes.o" "./mbedtls/EFR32/radioaes_ble.o" "./mbedtls/EFR32/ripemd160.o" "./mbedtls/EFR32/rsa.o" "./mbedtls/EFR32/rsa_internal.o" "./mbedtls/EFR32/se_aes.o" "./mbedtls/EFR32/se_ccm.o" "./mbedtls/EFR32/se_cmac.o" "./mbedtls/EFR32/se_ecp.o" "./mbedtls/EFR32/se_gcm.o" "./mbedtls/EFR32/se_jpake.o" "./mbedtls/EFR32/se_management.o" "./mbedtls/EFR32/se_sha.o" "./mbedtls/EFR32/se_trng.o" "./mbedtls/EFR32/sha1.o" "./mbedtls/EFR32/sha256.o" "./mbedtls/EFR32/sha512.o" "./mbedtls/EFR32/shax.o" "./mbedtls/EFR32/ssl_cache.o" "./mbedtls/EFR32/ssl_ciphersuites.o" "./mbedtls/EFR32/ssl_cli.o" "./mbedtls/EFR32/ssl_cookie.o" "./mbedtls/EFR32/ssl_srv.o" "./mbedtls/EFR32/ssl_ticket.o" "./mbedtls/EFR32/ssl_tls.o" "./mbedtls/EFR32/threading.o" "./mbedtls/EFR32/timing.o" "./mbedtls/EFR32/trng.o" "./mbedtls/EFR32/version.o" "./mbedtls/EFR32/version_features.o" "./mbedtls/EFR32/x509.o" "./mbedtls/EFR32/x509_create.o" "./mbedtls/EFR32/x509_crl.o" "./mbedtls/EFR32/x509_crt.o" "./mbedtls/EFR32/x509_csr.o" "./mbedtls/EFR32/x509write_crt.o" "./mbedtls/EFR32/x509write_csr.o" "./mbedtls/EFR32/xtea.o" "./mbedtls/EFR32_2_2/ba414ep_config.o" "./mbedtls/EFR32_2_2/ba431_config.o" "./mbedtls/EFR32_2_2/cryptodma_internal.o" "./mbedtls/EFR32_2_2/cryptolib_types.o" "./mbedtls/EFR32_2_2/sx_aes.o" "./mbedtls/EFR32_2_2/sx_blk_cipher.o" "./mbedtls/EFR32_2_2/sx_dh_alg.o" "./mbedtls/EFR32_2_2/sx_ecc_curves.o" "./mbedtls/EFR32_2_2/sx_ecc_keygen_alg.o" "./mbedtls/EFR32_2_2/sx_ecdsa_alg.o" "./mbedtls/EFR32_2_2/sx_hash.o" "./mbedtls/EFR32_2_2/sx_math.o" "./mbedtls/EFR32_2_2/sx_memcmp.o" "./mbedtls/EFR32_2_2/sx_memcpy.o" "./mbedtls/EFR32_2_2/sx_primitives.o" "./mbedtls/EFR32_2_2/sx_rng.o" "./mbedtls/EFR32_2_2/sx_trng.o" "./nvm3/EFR32/nvm3_default.o" "./nvm3/EFR32/nvm3_hal_flash.o" "./nvm3/nvm3_lock.o" "./serial/EFR32/serial.o" "./serial/com.o" "C:/SiliconLabs/SimplicityStudio/v4_2/developer/sdks/gecko_sdk_suite/v2.7//platform/emdrv/nvm3/lib/libnvm3_CM33_gcc.a" "C:/SiliconLabs/SimplicityStudio/v4_2/developer/sdks/gecko_sdk_suite/v2.7//platform/radio/rail_lib/autogen/librail_release/librail_efr32xg22_gcc_release.a" "C:/SiliconLabs/SimplicityStudio/v4_2/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/sim-eeprom2-to-nvm3-upgrade-stub-library-cortexm3-gcc-efr32mg22-rail/sim-eeprom2-to-nvm3-upgrade-stub-library.a" "C:/SiliconLabs/SimplicityStudio/v4_2/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/hal-library-cortexm3-gcc-efr32mg22-rail/hal-library.a" -lm -Wl,--end-group -Wl,--start-group -lgcc -lc -lnosys -Wl,--end-group
	@echo 'Finished building target: $@'
	@echo ' '

	@echo 'Building hex file: gpd_sensor_mg22_v673.hex'
	arm-none-eabi-objcopy -O ihex "gpd_sensor_mg22_v673.axf" "gpd_sensor_mg22_v673.hex"
	@echo ' '

	@echo 'Building bin file: gpd_sensor_mg22_v673.bin'
	arm-none-eabi-objcopy -O binary "gpd_sensor_mg22_v673.axf" "gpd_sensor_mg22_v673.bin"
	@echo ' '

	@echo 'Building s37 file: gpd_sensor_mg22_v673.s37'
	arm-none-eabi-objcopy -O srec "gpd_sensor_mg22_v673.axf" "gpd_sensor_mg22_v673.s37"
	@echo ' '

	@echo 'Running size tool'
	arm-none-eabi-size "gpd_sensor_mg22_v673.axf" -A
	@echo ' '

	$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(EXECUTABLES)$(OBJS)$(C_DEPS) gpd_sensor_mg22_v673.axf
	-@echo ' '

pre-build:
	-cmd //c 'C:\Users\alji\SIMPLI~1\V4_WOR~1\GPD_SE~2/gpd_sensor_mg22_v673-prebuild.bat' 'gpd_sensor_mg22_v673' 'C:/Users/alji/SimplicityStudio/v4_workspace/gpd_sensor_mg22_v673' '' 'C:\SiliconLabs\SimplicityStudio\v4_2'
	-@echo ' '

post-build:
	-cmd //c 'C:\Users\alji\SIMPLI~1\V4_WOR~1\GPD_SE~2/gpd_sensor_mg22_v673-postbuild.bat' 'gpd_sensor_mg22_v673' 'C:/Users/alji/SimplicityStudio/v4_workspace/gpd_sensor_mg22_v673' '' 'C:\SiliconLabs\SimplicityStudio\v4_2'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: main-build pre-build post-build

-include ../makefile.targets
