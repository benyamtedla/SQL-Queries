SQL Queries :2
CREATE TABLE employees (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    first_name  VARCHAR(14)     NOT NULL,
    last_name   VARCHAR(16)     NOT NULL,
    email VARCHAR(200) NOT NULL UNIQUE,    
    phone VARCHAR(200),
 address VARCHAR(200)
);

INSERT INTO `employees` (first_name, last_name, email, phone, address) VALUES 
('Bill','Gates','bill.gates@microsoft.com','+100100100','Washington, USA'),
('Will','Smith','will@gmail.com','+111222333','Arizona, USA'),
('Georgi','Facello','Georgi@gmail.com','+123123123','New York, USA'),
('Bezalel','Simmel','Bezalel@gmail.com','+122122122','California, USA'),
('Parto','Bamford','Parto@gmail.com','+124124124','Chicago, USA'),
('Chirstian','Koblick','Chirstian@gmail.com','+125125125','New York, USA'),
('Kyoichi','Maliniak','Kyoichi@gmail.com','+126126126','California, USA'),
('Anneke','Preusig','Anneke@gmail.com','+127127127','Chicago, USA'),
('Tzvetan','Zielinski','Tzvetan@gmail.com','+128128128','New York, USA'),
('Saniya','Kalloufi','Saniya@gmail.com','+129129129','California, USA'),
('Sumant','Peac','Sumant@gmail.com','+130130130','Chicago, USA'),
('Duangkaew','Piveteau','Duangkaew@gmail.com','+131131131','New York, USA'),
('Mary','Sluis','Mary@gmail.com','+132132132','Chicago, USA'); .
