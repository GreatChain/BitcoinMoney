.PHONY: FORCE
all: FORCE
	$(MAKE) -C .. bitcoin_money test_bitcoin_money
clean: FORCE
	$(MAKE) -C .. bitcoin_money_clean test_bitcoin_money_clean
check: FORCE
	$(MAKE) -C .. test_bitcoin_qt_check
bitcoin_money bitcoin_money.exe: FORCE
	 $(MAKE) -C .. bitcoin_money
