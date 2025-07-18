# m4son_studio_phone
Latest Iphone 15 Pro in a Fivem Server QB/ESX


# M4SON1 Studio Phone - FiveM Resource

A comprehensive FiveM phone resource featuring iPhone 15 Pro Max design with full ESX and QBCore compatibility.

## Features

- **Authentic iPhone 15 Pro Max Design**: Realistic UI with Dynamic Island
- **Multiple Phone Variants**: 13 different iPhone models with unique colors
- **Framework Compatibility**: Auto-detects ESX, QBCore, or runs standalone
- **Full Phone Functionality**: Calls, messages, contacts, GPS, camera, banking, and more
- **F1 Key Binding**: Easy phone toggle with F1 key
- **Inventory Integration**: Complete item system with beautiful inventory images

## Phone Variants

### iPhone 15 Pro Max Series (Legendary)
- Black Titanium - $1,200
- White Titanium - $1,200  
- Blue Titanium - $1,200
- Natural Titanium - $1,200

### iPhone 15 Pro Series (Epic)
- Black Titanium - $1,000
- White Titanium - $1,000
- Blue Titanium - $1,000
- Natural Titanium - $1,000

### iPhone 15 Series (Rare)
- Pink - $800
- Yellow - $800
- Green - $800
- Blue - $800
- Black - $800

## Installation

### 1. Prerequisites
- FiveM Server
- oxmysql resource
- ESX or QBCore framework (optional)

### 2. Installation Steps

1. **Download the Resource**
   ```bash
   # Place in your resources folder
   resources/m4son1_studio_phone/
   ```

2. **Install Dependencies**
   ```bash
   # Make sure oxmysql is installed
   ensure oxmysql
   ```

3. **Database Setup**
   - Import `sql/phone_database.sql` to your database
   - Import `items.sql` to add phone items to your inventory system

4. **Server Configuration**
   Add to your `server.cfg`:
   ```
   ensure oxmysql
   ensure m4son1_studio_phone
   ```

5. **Add Phone Items**
   - **ESX**: Import items from `items.sql` into your `items` table
   - **QBCore**: Copy items from `items.sql` into your `qb-core/shared/items.lua`

6. **Copy Inventory Images**
   Copy all PNG files from `html/assets/inventory/inventory_images/` to your inventory script's images folder.

## Usage

### Controls
- **F1 Key**: Toggle phone on/off
- **ESC Key**: Close phone or go back
- **Mouse**: Navigate through interface

### Admin Commands
```bash
# Give specific phone to player
givephone <playerid> <phone_id>

# Example:
givephone 1 iphone_15_pro_max_black
```

### Available Phone IDs
- `iphone_15_pro_max_black`
- `iphone_15_pro_max_white`
- `iphone_15_pro_max_blue`
- `iphone_15_pro_max_natural`
- `iphone_15_pro_black`
- `iphone_15_pro_white`
- `iphone_15_pro_blue`
- `iphone_15_pro_natural`
- `iphone_15_pink`
- `iphone_15_yellow`
- `iphone_15_green`
- `iphone_15_blue`
- `iphone_15_black`

## Apps Included

- **Phone**: Make calls to other players
- **Messages**: Send/receive text messages
- **Contacts**: Manage contact list
- **Maps**: GPS navigation system
- **Camera**: Take photos
- **Photos**: View photo gallery
- **Music**: Music player
- **Weather**: Weather information
- **Banking**: Account management (ESX/QBCore integration)
- **Email**: Email system
- **Calendar**: Calendar with events
- **Notes**: Take notes
- **Clock**: Time and alarms
- **Calculator**: Basic calculator
- **Settings**: Phone settings

## Configuration

Edit `config.lua` to customize:
- Phone animations and timings
- Feature toggles
- Framework settings
- Phone color variants

## Framework Integration

The resource automatically detects and integrates with:
- **ESX**: Full economy integration
- **QBCore**: Complete framework support
- **Standalone**: Works without framework

## Support

For support and updates, visit the M4SON1 Studio community.

## License

This resource is created by M4SON1 Studio for the FiveM community.
