package tictactoe;

public class Home extends javax.swing.JFrame {

    public int player = 1, win = 0;
    public int x1 = 0, x2 = 0, x3 = 0, x4 = 0, x5 = 0, x6 = 0, x7 = 0, x8 = 0, x9 = 0;
    public int y1 = 0, y2 = 0, y3 = 0, y4 = 0, y5 = 0, y6 = 0, y7 = 0, y8 = 0, y9 = 0;

    public Home() {
        initComponents();
    }

    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jLabel1 = new javax.swing.JLabel();
        b1 = new javax.swing.JButton();
        b2 = new javax.swing.JButton();
        b3 = new javax.swing.JButton();
        b4 = new javax.swing.JButton();
        b5 = new javax.swing.JButton();
        b7 = new javax.swing.JButton();
        b8 = new javax.swing.JButton();
        b9 = new javax.swing.JButton();
        b6 = new javax.swing.JButton();
        reset = new javax.swing.JButton();
        l2 = new javax.swing.JLabel();
        jLabel2 = new javax.swing.JLabel();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        jLabel1.setFont(new java.awt.Font("Times New Roman", 1, 12)); // NOI18N
        jLabel1.setHorizontalAlignment(javax.swing.SwingConstants.CENTER);
        jLabel1.setText("Player 1 = O And Player 2 = X");

        b1.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b1ActionPerformed(evt);
            }
        });

        b2.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b2ActionPerformed(evt);
            }
        });

        b3.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b3ActionPerformed(evt);
            }
        });

        b4.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b4.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b4ActionPerformed(evt);
            }
        });

        b5.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b5.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b5ActionPerformed(evt);
            }
        });

        b7.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b7.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b7ActionPerformed(evt);
            }
        });

        b8.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b8ActionPerformed(evt);
            }
        });

        b9.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b9.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b9ActionPerformed(evt);
            }
        });

        b6.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        b6.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                b6ActionPerformed(evt);
            }
        });

        reset.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        reset.setText("Reset");
        reset.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                resetActionPerformed(evt);
            }
        });

        l2.setFont(new java.awt.Font("Times New Roman", 1, 14)); // NOI18N
        l2.setHorizontalAlignment(javax.swing.SwingConstants.CENTER);

        jLabel2.setBackground(new java.awt.Color(255, 255, 255));
        jLabel2.setFont(new java.awt.Font("SimSun", 1, 36)); // NOI18N
        jLabel2.setHorizontalAlignment(javax.swing.SwingConstants.CENTER);
        jLabel2.setText("Tic Tac Toe");

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(62, 62, 62)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(reset, javax.swing.GroupLayout.PREFERRED_SIZE, 97, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(l2, javax.swing.GroupLayout.PREFERRED_SIZE, 136, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel1, javax.swing.GroupLayout.PREFERRED_SIZE, 198, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, 111, Short.MAX_VALUE)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(b1, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(b7, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(b4, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(54, 54, 54)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(b5, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(b8, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)))
                    .addGroup(layout.createSequentialGroup()
                        .addGap(64, 64, 64)
                        .addComponent(b2, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addGap(42, 42, 42)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(b3, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(b9, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(b6, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(101, 101, 101))
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jLabel2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                .addContainerGap())
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jLabel2, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, 59, Short.MAX_VALUE)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                        .addComponent(jLabel1, javax.swing.GroupLayout.PREFERRED_SIZE, 37, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addComponent(l2, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(61, 61, 61)
                        .addComponent(reset, javax.swing.GroupLayout.PREFERRED_SIZE, 83, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                            .addComponent(b1, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                            .addComponent(b2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                            .addComponent(b3, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addGap(51, 51, 51)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(b6, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(b5, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(b4, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addGap(47, 47, 47)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(b7, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(b8, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(b9, javax.swing.GroupLayout.PREFERRED_SIZE, 62, javax.swing.GroupLayout.PREFERRED_SIZE))))
                .addGap(65, 65, 65))
        );

        pack();
    }// </editor-fold>                        

    private void b3ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y3 == 0) {
            y3 = 1;
            if (player == 1) {
                player = 2;
                b3.setText("O");
                x3 = 1;
            } else if (player == 2) {
                player = 1;
                b3.setText("X");
                x3 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b4ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y4 == 0) {
            y4 = 1;
            if (player == 1) {
                player = 2;
                b4.setText("O");
                x4 = 1;
            } else if (player == 2) {
                player = 1;
                b4.setText("X");
                x4 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b7ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y7 == 0) {
            y7 = 1;
            if (player == 1) {
                player = 2;
                b7.setText("O");
                x7 = 1;
            } else if (player == 2) {
                player = 1;
                b7.setText("X");
                x7 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b9ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y9 == 0) {
            y9 = 1;
            if (player == 1) {
                player = 2;
                b9.setText("O");
                x9 = 1;
            } else if (player == 2) {
                player = 1;
                b9.setText("X");
                x9 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b1ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y1 == 0) {
            y1 = 1;
            if (player == 1) {
                player = 2;
                b1.setText("O");
                x1 = 1;
            } else if (player == 2) {
                player = 1;
                b1.setText("X");
                x1 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b2ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y2 == 0) {
            y2 = 1;
            if (player == 1) {
                player = 2;
                b2.setText("O");
                x2 = 1;
            } else if (player == 2) {
                player = 1;
                b2.setText("X");
                x2 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b5ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y5 == 0) {
            y5 = 1;
            if (player == 1) {
                player = 2;
                b5.setText("O");
                x5 = 1;
            } else if (player == 2) {
                player = 1;
                b5.setText("X");
                x5 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b6ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y6 == 0) {
            y6 = 1;
            if (player == 1) {
                player = 2;
                b6.setText("O");
                x6 = 1;
            } else if (player == 2) {
                player = 1;
                b6.setText("X");
                x6 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void b8ActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        if (win == 0 && y8 == 0) {
            y8 = 1;
            if (player == 1) {
                player = 2;
                b8.setText("O");
                x8 = 1;
            } else if (player == 2) {
                player = 1;
                b8.setText("X");
                x8 = 2;
            }
            if (x1 == 1 && x2 == 1 && x3 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x2 == 2 && x3 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x4 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x4 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x6 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x3 == 2 && x6 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x7 == 1 && x8 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x7 == 2 && x8 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x1 == 1 && x5 == 1 && x9 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x1 == 2 && x5 == 2 && x9 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x3 == 1 && x5 == 1 && x7 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x5 == 2 && x3 == 2 && x7 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x2 == 1 && x5 == 1 && x8 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x2 == 2 && x5 == 2 && x8 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            } else if (x4 == 1 && x5 == 1 && x6 == 1) {
                l2.setText("Player 1 Is Win");
                win = 1;
            } else if (x4 == 2 && x5 == 2 && x6 == 2) {
                l2.setText("Player 2 Is Win");
                win = 1;
            }
        }
    }                                  

    private void resetActionPerformed(java.awt.event.ActionEvent evt) {                                      
        // TODO add your handling code here:
        b1.setText("");
        b2.setText("");
        b3.setText("");
        b4.setText("");
        b5.setText("");
        b6.setText("");
        b7.setText("");
        b8.setText("");
        b9.setText("");
        l2.setText("");
        x1 = 0;
        x2 = 0;
        x3 = 0;
        x4 = 0;
        x5 = 0;
        x6 = 0;
        x7 = 0;
        x8 = 0;
        x9 = 0;
        y1 = 0;
        y2 = 0;
        y3 = 0;
        y4 = 0;
        y5 = 0;
        y6 = 0;
        y7 = 0;
        y8 = 0;
        y9 = 0;
        win = 0;
        player = 1;
    }                                     

    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(Home.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(Home.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(Home.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(Home.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new Home().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton b1;
    private javax.swing.JButton b2;
    private javax.swing.JButton b3;
    private javax.swing.JButton b4;
    private javax.swing.JButton b5;
    private javax.swing.JButton b6;
    private javax.swing.JButton b7;
    private javax.swing.JButton b8;
    private javax.swing.JButton b9;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabel2;
    private javax.swing.JLabel l2;
    private javax.swing.JButton reset;
    // End of variables declaration                   
}
