# Aragon Plugin Development

This project is set up for developing custom plugins for Aragon OSx using Foundry.

## Dependencies

- [Foundry](https://book.getfoundry.sh/) - Ethereum development toolkit
- [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts/) - Secure smart contract library
- [Aragon OSx](https://github.com/aragon/osx) - Aragon plugin framework

## Project Structure

```
├── src/           # Plugin contracts go here
├── test/          # Test files
├── script/        # Deployment scripts
└── lib/           # Dependencies
```

## Getting Started

### Build

```shell
forge build
```

### Test

```shell
forge test
```

### Format

```shell
forge fmt
```

### Deploy

```shell
forge script script/YourPlugin.s.sol:YourPluginScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

## Resources

- [Aragon OSx Documentation](https://devs.aragon.org/)
- [Foundry Book](https://book.getfoundry.sh/)
- [OpenZeppelin Docs](https://docs.openzeppelin.com/)
