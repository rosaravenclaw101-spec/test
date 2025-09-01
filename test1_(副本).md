test1
![006i3hfEgy1he1tho3b0qj32681mob2a.jpg](http://localhost:8080/uploads/2025/09/01/202213_7283270e.jpg)> 
```javascript
Map<String, Object> result = new HashMap<>();
        result.put("filename", filename);
        result.put("originalName", file.getOriginalFilename());
        result.put("url", baseUrl + "/uploads/" + filename);
        result.put("size", file.getSize());
        result.put("uploadTime", LocalDateTime.now().format(DateTimeFormatter.ISO_LOCAL_DATE_TIME));
```