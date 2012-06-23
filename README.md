# OSGB36 Conversion tools

### OSGB36 Eastings/Northings Coords to WGS84 Lat/Lon

```ruby
OSGB36.en_to_ll(easting,northing) 
#=> { :latitude => latitude, :longitude => longitude }
```

### OSGB36 Eastings/Northings Coords to OSGB36 Lat/Lon

```ruby
OSGB36.to_OSGB36(easting,northing) 
#=> { :latitude => latitude, :longitude => longitude }
```

### OSGB36 Eastings/Northings Coords to WGS84 Lat/Lon

```ruby
OSGB36.to_WGS84(latitude,longitude) 
#=> { :latitude => latitude, :longitude => longitude }
```