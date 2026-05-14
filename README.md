# Courier Management System

**Version:** 1.0  
**Category:** Uncategorized  
**License:** LGPL-3  

## Description

Courier-style request -> internal request order flow with FinCodeMaster and transit hubs

## Features

- Odoo 19.0 compatible
- Standalone application
- Courier-style request -> internal request order flow with FinCodeMaster and transit hubs

## Dependencies

This module depends on the following Odoo modules:

- `sale`
- `stock`
- `account`
- `mail`
- `sale_management`
- `purchase`
- `fleet`
- `portal`
- `vendor_dispatch_portal_v2`

## Installation

1. Clone this repository into your Odoo addons directory:
   ```bash
   git clone https://github.com/tejas7287/courier_management_final.git
   ```

2. Add the module path to your Odoo configuration file (`odoo.conf`):
   ```
   addons_path = /path/to/odoo/addons,/path/to/courier_management_final
   ```

3. Restart the Odoo server:
   ```bash
   sudo systemctl restart odoo
   ```

4. Go to **Apps** → **Update Apps List** → Search for **"Courier Management System"** → Click **Install**

## Module Structure

```
courier_management_final/
├── __init__.py
├── __manifest__.py
├── models/
├── report/
├── security/
├── views/
```

## Configuration

After installation, configure the module through Odoo's Settings menu or the module's specific configuration options.

## License

This project is licensed under the LGPL-3 License.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
