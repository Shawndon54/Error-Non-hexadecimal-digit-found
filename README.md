brownie run scripts/get_weth.py --network kovan
Brownie v1.14.6 - Python development framework for Ethereum

AaveFlashloanMixMasterProject is the active project.

Running 'scripts/get_weth.py::main'...
  File "eth_brownie-1.14.6-py3.9.egg/brownie/_cli/run.py", line 49, in main
    return_value, frame = run(
  File "eth_brownie-1.14.6-py3.9.egg/brownie/project/scripts.py", line 103, in run
    return_value = f_locals[method_name](*args, **kwargs)
  File "./scripts/get_weth.py", line 8, in main
    get_weth()
  File "./scripts/get_weth.py", line 15, in get_weth
    acct = accounts.add(
  File "eth_brownie-1.14.6-py3.9.egg/brownie/network/account.py", line 135, in add
    w3account = web3.eth.account.from_key(private_key)
  File "eth_utils-1.10.0-py3.9.egg/eth_utils/decorators.py", line 18, in _wrapper
    return self.method(obj, *args, **kwargs)
  File "eth_account-0.5.4-py3.9.egg/eth_account/account.py", line 246, in from_key
    key = self._parsePrivateKey(private_key)
  File "eth_utils-1.10.0-py3.9.egg/eth_utils/decorators.py", line 18, in _wrapper
    return self.method(obj, *args, **kwargs)
  File "eth_account-0.5.4-py3.9.egg/eth_account/account.py", line 694, in _parsePrivateKey
    return self._keys.PrivateKey(HexBytes(key))
  File "hexbytes-0.2.1-py3.9.egg/hexbytes/main.py", line 23, in __new__
    bytesval = to_bytes(val)
  File "hexbytes-0.2.1-py3.9.egg/hexbytes/_utils.py", line 17, in to_bytes
    return hexstr_to_bytes(val)
  File "hexbytes-0.2.1-py3.9.egg/hexbytes/_utils.py", line 50, in hexstr_to_bytes
    return binascii.unhexlify(ascii_hex)
Error: Non-hexadecimal digit found

decode('hex')
bash: syntax error near unexpected token `'hex''
