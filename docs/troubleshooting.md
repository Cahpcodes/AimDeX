# Troubleshooting Guide

Common issues and their solutions for AimDeX.

## Installation Issues

### Windows Defender Blocking

**Problem**: Windows Defender flags AimDeX as a threat.

**Solution**: 
1. Add an exception in Windows Security
2. Download from official releases only
3. Verify file integrity

### Missing Dependencies

**Problem**: Application won't start due to missing .NET runtime.

**Solution**: Install .NET 6.0 Runtime from Microsoft.

## Runtime Issues

### Application Not Starting

**Checklist**:
- Run as administrator
- Check antivirus settings
- Verify system requirements
- Check event logs

### Detection Not Working

**Solutions**:
- Adjust confidence threshold
- Verify model is loaded
- Check detection area settings
- Ensure GPU drivers are updated

### High CPU/GPU Usage

**Solutions**:
- Lower detection resolution
- Adjust frame rate limits
- Close background applications
- Check for driver updates

## Configuration Issues

### Settings Not Saving

**Solution**: Ensure AimDeX has write permissions to its directory.

### Hotkeys Not Working

**Solutions**:
- Check for conflicts with other applications
- Run as administrator
- Verify hotkey assignments

## Need More Help?

- Join our [Discord](https://discord.gg/aimdex)
- Check [GitHub Issues](https://github.com/Cahpcodes/AimDeX/issues)
- Review [Getting Started Guide](./getting-started.md)
