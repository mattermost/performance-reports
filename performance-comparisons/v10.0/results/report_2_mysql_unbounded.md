### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 147ms | 147ms | 2395657.17
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 30ms | 366ms | 336ms | 1128.04
| TokenStore.Cleanup | avg | 2ms | 19ms | 17ms | 767.36
| ChannelStore.CreateSidebarCategory | avg | 19ms | 155ms | 136ms | 713.79
| CommandWebhookStore.Cleanup | avg | 3ms | 18ms | 15ms | 543.94
| StatusStore.SaveOrUpdate | avg | 10ms | 30ms | 20ms | 201.61
| EmojiStore.GetMultipleByName | avg | 111ms | 284ms | 173ms | 156.31
| ChannelStore.AnalyticsTypeCount | avg | 81ms | 129ms | 48ms | 59.58
| UserStore.GetMany | avg | 118ms | 176ms | 58ms | 49.11
| PostStore.AnalyticsPostCount | avg | 1.367s | 1.905s | 538ms | 39.36
| PostStore.SetPostReminder | avg | 12ms | 15ms | 3ms | 25.57
| TeamStore.AnalyticsTeamCount | avg | 71ms | 88ms | 17ms | 24.10
| UserStore.Update | avg | 9ms | 11ms | 2ms | 22.43
| UserAccessTokenStore.GetByToken | avg | 113ms | 137ms | 24ms | 21.17
| UserStore.Count | avg | 315ms | 375ms | 60ms | 19.03
| PostStore.Delete | avg | 116ms | 135ms | 19ms | 16.42
| PluginStore.List | avg | 132ms | 144ms | 12ms | 9.07
| StatusStore.Get | avg | 72ms | 78ms | 6ms | 8.37
| ProductNoticesStore.View | avg | 37ms | 40ms | 3ms | 8.11
| UserStore.GetProfilesInChannel | avg | 103ms | 111ms | 8ms | 7.79
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 109ms | 115ms | 6ms | 5.51
| UserStore.GetAllProfiles | avg | 95ms | 99ms | 4ms | 4.19
| ChannelStore.GetByName | avg | 109ms | 113ms | 4ms | 3.65
| ChannelStore.CreateDirectChannel | avg | 522ms | 541ms | 19ms | 3.64
| UserStore.IsEmpty | avg | 59ms | 61ms | 2ms | 3.40
| UserStore.AnalyticsActiveCount | avg | 588ms | 607ms | 19ms | 3.23
| ChannelStore.CreateInitialSidebarCategories | avg | 122ms | 125ms | 3ms | 2.47
| TeamStore.GetAllPage | avg | 122ms | 125ms | 3ms | 2.46
| TeamStore.SaveMember | avg | 215ms | 220ms | 5ms | 2.33
| ChannelStore.SaveMember | avg | 470ms | 480ms | 10ms | 2.13
| ChannelStore.GetGuestCount | avg | 148ms | 151ms | 3ms | 2.03
| ChannelStore.GetMemberLastViewedAt | avg | 102ms | 104ms | 2ms | 1.96
| ThreadStore.GetTotalThreads | avg | 121ms | 123ms | 2ms | 1.66
| UserTermsOfServiceStore.GetByUser | avg | 138ms | 140ms | 2ms | 1.45
| FileInfoStore.GetByIds | avg | 172ms | 174ms | 2ms | 1.16
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 857ms | 852ms | 17211.65
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 99ms | 2.44s | 2.341s | 2364.65
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 495ms | 470ms | 1891.35
| TokenStore.Cleanup | p99 | 10ms | 49ms | 39ms | 397.96
| CommandWebhookStore.Cleanup | p99 | 10ms | 49ms | 39ms | 397.96
| ChannelStore.AnalyticsTypeCount | p99 | 245ms | 910ms | 665ms | 270.88
| PostStore.Delete | p99 | 247ms | 900ms | 653ms | 264.69
| StatusStore.SaveOrUpdate | p99 | 142ms | 458ms | 316ms | 222.86
| UserStore.GetMany | p99 | 890ms | 2.17s | 1.28s | 143.82
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 98ms | 238ms | 140ms | 142.13
| UserStore.AnalyticsActiveCount | p99 | 994ms | 2.23s | 1.236s | 124.35
| ChannelStore.GetMembersForUserWithPagination | p99 | 947ms | 2.095s | 1.148s | 121.16
| EmojiStore.GetMultipleByName | p99 | 452ms | 960ms | 508ms | 112.27
| TeamStore.AnalyticsTeamCount | p99 | 245ms | 478ms | 233ms | 94.91
| LicenseStore.GetAll | p99 | 488ms | 910ms | 422ms | 86.56
| UserStore.Update | p99 | 100ms | 185ms | 85ms | 85.21
| PluginStore.List | p99 | 870ms | 1.6s | 730ms | 83.91
| FileInfoStore.GetByIds | p99 | 966ms | 1.695s | 729ms | 75.44
| ChannelStore.CreateDirectChannel | p99 | 3.113s | 4.025s | 912ms | 29.30
| JobStore.UpdateStatus | p99 | 47ms | 60ms | 13ms | 27.90
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 1.08s | 1.332s | 252ms | 23.33
| StatusStore.Get | p99 | 665ms | 786ms | 121ms | 18.19
| UserStore.IsEmpty | p99 | 570ms | 668ms | 98ms | 17.20
| UserStore.UpdateUpdateAt | p99 | 58ms | 67ms | 9ms | 15.43
| ChannelStore.UpdateSidebarCategories | p99 | 2.005s | 2.28s | 275ms | 13.72
| PostStore.Update | p99 | 215ms | 237ms | 22ms | 10.23
| ProductNoticesStore.View | p99 | 394ms | 434ms | 40ms | 10.14
| JobStore.UpdateOptimistically | p99 | 92ms | 97ms | 5ms | 5.43
| ThreadStore.UpdateMembership | p99 | 88ms | 92ms | 4ms | 4.55
| PreferenceStore.Save | p99 | 201ms | 210ms | 9ms | 4.47
| UserStore.UpdateLastLogin | p99 | 69ms | 72ms | 3ms | 4.35
| ChannelStore.GetGuestCount | p99 | 1.226s | 1.276s | 50ms | 4.08
| UserStore.UpdateFailedPasswordAttempts | p99 | 74ms | 77ms | 3ms | 4.04
| AuditStore.Save | p99 | 75ms | 78ms | 3ms | 3.99
| SystemStore.GetByName | p99 | 54ms | 56ms | 2ms | 3.69
| StatusStore.UpdateLastActivityAt | p99 | 85ms | 88ms | 3ms | 3.53
| UserStore.GetAllProfiles | p99 | 915ms | 945ms | 30ms | 3.28
| ChannelStore.Save | p99 | 1.84s | 1.9s | 60ms | 3.26
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 63ms | 65ms | 2ms | 3.18
| ChannelStore.GetMember | p99 | 193ms | 199ms | 6ms | 3.12
| ChannelStore.UpdateLastViewedAt | p99 | 156ms | 160ms | 4ms | 2.56
| PostStore.SetPostReminder | p99 | 209ms | 213ms | 4ms | 1.91
| ThreadStore.GetTotalUnreadMentions | p99 | 988ms | 1.001s | 13ms | 1.32
| UserStore.GetProfileByIds | p99 | 963ms | 974ms | 11ms | 1.14
| ThreadStore.MaintainMembership | p99 | 189ms | 191ms | 2ms | 1.06
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 0s | -2ms | -108.84
| TeamStore.GetMany | avg | 159ms | 0s | -159ms | -100.11
| ChannelStore.GetMembers | avg | 98ms | 0s | -98ms | -100.10
| PostStore.GetPostsByIds | avg | 112ms | 0s | -112ms | -99.97
| ChannelStore.GetChannelsByIds | avg | 187ms | 0s | -187ms | -99.78
| ChannelStore.GetByNameIncludeDeleted | avg | 75ms | 0s | -75ms | -99.37
| RetentionPolicyStore.GetCount | avg | 190ms | 1ms | -189ms | -99.26
| RetentionPolicyStore.GetAll | avg | 177ms | 3ms | -174ms | -98.32
| PluginStore.Get | avg | 495ms | 83ms | -412ms | -83.26
| PostPersistentNotificationStore.UpdateLastActivity | avg | 2ms | 0s | -2ms | -81.66
| PreferenceStore.DeleteCategoryAndName | avg | 22ms | 6ms | -16ms | -74.00
| PostStore.GetPostReminders | avg | 11ms | 4ms | -7ms | -63.10
| JobStore.GetAllByTypePage | avg | 245ms | 96ms | -149ms | -60.73
| SessionStore.GetSessionsExpired | avg | 168ms | 68ms | -100ms | -59.46
| ProductNoticesStore.GetViews | avg | 59ms | 26ms | -33ms | -55.55
| LinkMetadataStore.Save | avg | 11ms | 5ms | -6ms | -54.22
| JobStore.GetCountByStatusAndType | avg | 217ms | 101ms | -116ms | -53.55
| ThreadStore.Get | avg | 254ms | 123ms | -131ms | -51.59
| SessionStore.Remove | avg | 12ms | 7ms | -5ms | -41.57
| UserStore.GetProfilesNotInChannel | avg | 276ms | 163ms | -113ms | -40.92
| RoleStore.ChannelHigherScopedPermissions | avg | 187ms | 113ms | -74ms | -39.53
| BotStore.Get | avg | 187ms | 117ms | -70ms | -37.46
| StatusStore.UpdateExpiredDNDStatuses | avg | 9ms | 6ms | -3ms | -35.06
| PostAcknowledgementStore.GetForPost | avg | 164ms | 108ms | -56ms | -34.07
| JobStore.GetNewestJobByStatusesAndType | avg | 174ms | 116ms | -58ms | -33.34
| UserStore.Get | avg | 78ms | 53ms | -25ms | -32.18
| LicenseStore.GetAll | avg | 125ms | 85ms | -40ms | -31.92
| JobStore.UpdateStatusOptimistically | avg | 10ms | 7ms | -3ms | -31.34
| ChannelStore.GetChannelUnread | avg | 188ms | 133ms | -55ms | -29.29
| JobStore.Save | avg | 7ms | 5ms | -2ms | -28.39
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 43ms | 31ms | -12ms | -27.80
| PostStore.GetPostsAfter | avg | 177ms | 131ms | -46ms | -25.94
| ChannelStore.AutocompleteInTeamForSearch | avg | 670ms | 508ms | -162ms | -24.19
| UserStore.AnalyticsGetInactiveUsersCount | avg | 48ms | 37ms | -11ms | -22.95
| ComplianceStore.MessageExport | avg | 186ms | 144ms | -42ms | -22.55
| ChannelStore.GetTeamChannels | avg | 268ms | 209ms | -59ms | -22.00
| ChannelStore.GetSidebarCategory | avg | 221ms | 175ms | -46ms | -20.86
| ChannelStore.GetFileCount | avg | 125ms | 99ms | -26ms | -20.77
| JobStore.Get | avg | 234ms | 188ms | -46ms | -19.67
| ChannelStore.Save | avg | 235ms | 197ms | -38ms | -16.15
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 199ms | 167ms | -32ms | -16.05
| PostStore.SearchPostsForUser | avg | 251ms | 211ms | -40ms | -15.96
| FileInfoStore.SetContent | avg | 13ms | 11ms | -2ms | -15.85
| ChannelStore.GetPinnedPostCount | avg | 180ms | 152ms | -28ms | -15.54
| TeamStore.GetActiveMemberCount | avg | 613ms | 521ms | -92ms | -15.01
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 1.02s | 867ms | -153ms | -15.00
| PostPriorityStore.GetForPost | avg | 146ms | 125ms | -21ms | -14.34
| ChannelStore.SearchGroupChannels | avg | 192ms | 165ms | -27ms | -14.08
| ChannelStore.GetPublicChannelsForTeam | avg | 215ms | 186ms | -29ms | -13.51
| StatusStore.GetByIds | avg | 192ms | 169ms | -23ms | -11.98
| ReactionStore.GetForPost | avg | 179ms | 158ms | -21ms | -11.70
| ChannelStore.GetAllChannelMembersForUser | avg | 97ms | 86ms | -11ms | -11.31
| TeamStore.GetTotalMemberCount | avg | 659ms | 585ms | -74ms | -11.22
| FileInfoStore.Get | avg | 121ms | 108ms | -13ms | -10.74
| PostStore.GetSingle | avg | 172ms | 154ms | -18ms | -10.49
| UserStore.GetUnreadCount | avg | 145ms | 130ms | -15ms | -10.34
| LinkMetadataStore.Get | avg | 174ms | 157ms | -17ms | -9.78
| PostStore.Get | avg | 295ms | 267ms | -28ms | -9.49
| ThreadStore.GetThreadUnreadReplyCount | avg | 192ms | 174ms | -18ms | -9.38
| TeamStore.Get | avg | 165ms | 150ms | -15ms | -9.10
| JobStore.GetAllByStatus | avg | 171ms | 156ms | -15ms | -8.77
| PostStore.GetPostReminderMetadata | avg | 185ms | 169ms | -16ms | -8.64
| ChannelStore.UpdateSidebarCategories | avg | 394ms | 361ms | -33ms | -8.39
| UserStore.GetProfilesByUsernames | avg | 132ms | 121ms | -11ms | -8.34
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 134ms | 123ms | -11ms | -8.19
| ChannelStore.GetChannelsByUser | avg | 148ms | 136ms | -12ms | -8.12
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 152ms | 140ms | -12ms | -7.88
| DraftStore.Get | avg | 206ms | 190ms | -16ms | -7.77
| ThreadStore.GetThreadForUser | avg | 259ms | 239ms | -20ms | -7.72
| PreferenceStore.Get | avg | 162ms | 150ms | -12ms | -7.39
| ChannelStore.GetMemberCount | avg | 557ms | 516ms | -41ms | -7.36
| PostStore.GetPostsByThread | avg | 179ms | 166ms | -13ms | -7.26
| ChannelStore.GetMemberForPost | avg | 198ms | 184ms | -14ms | -7.08
| PostStore.GetPostsSince | avg | 217ms | 202ms | -15ms | -6.90
| PostPriorityStore.GetForPosts | avg | 278ms | 259ms | -19ms | -6.84
| WebhookStore.GetOutgoingByTeam | avg | 177ms | 165ms | -12ms | -6.80
| PostAcknowledgementStore.GetForPosts | avg | 270ms | 252ms | -18ms | -6.67
| PostStore.GetPostsBefore | avg | 165ms | 154ms | -11ms | -6.66
| ChannelStore.GetChannels | avg | 168ms | 158ms | -10ms | -5.94
| ThreadStore.GetMembershipForUser | avg | 170ms | 160ms | -10ms | -5.87
| UserStore.GetByUsername | avg | 171ms | 161ms | -10ms | -5.85
| ChannelStore.Autocomplete | avg | 3.994s | 3.764s | -230ms | -5.76
| UserStore.AutocompleteUsersInChannel | avg | 766ms | 722ms | -44ms | -5.74
| GroupStore.GetGroups | avg | 167ms | 158ms | -9ms | -5.39
| UserStore.Search | avg | 409ms | 388ms | -21ms | -5.13
| ChannelStore.GetMembersForUser | avg | 162ms | 154ms | -8ms | -4.95
| ThreadStore.GetThreadsForUser | avg | 189ms | 180ms | -9ms | -4.77
| ThreadStore.GetTeamsUnreadForUser | avg | 173ms | 165ms | -8ms | -4.62
| ThreadStore.GetThreadFollowers | avg | 175ms | 167ms | -8ms | -4.57
| ChannelStore.GetMembersForUserWithPagination | avg | 159ms | 152ms | -7ms | -4.42
| UserStore.GetAllProfilesInChannel | avg | 1.251s | 1.196s | -55ms | -4.40
| PostStore.GetEtag | avg | 159ms | 153ms | -6ms | -3.78
| PostPersistentNotificationStore.GetSingle | avg | 176ms | 170ms | -6ms | -3.41
| FileInfoStore.GetForPost | avg | 183ms | 178ms | -5ms | -2.73
| TeamStore.GetTeamsForUser | avg | 96ms | 94ms | -2ms | -2.09
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 168ms | 166ms | -2ms | -1.19
| ChannelStore.Get | avg | 199ms | 197ms | -2ms | -1.01
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 100ms | 0s | -100ms | -100.45
| PostStore.GetPostsByIds | p99 | 247ms | 0s | -247ms | -99.93
| TeamStore.GetMany | p99 | 492ms | 0s | -492ms | -99.90
| ChannelStore.GetChannelsByIds | p99 | 492ms | 0s | -492ms | -99.90
| ChannelStore.GetMembers | p99 | 246ms | 0s | -246ms | -99.88
| RetentionPolicyStore.GetCount | p99 | 493ms | 5ms | -488ms | -99.09
| RetentionPolicyStore.GetAll | p99 | 248ms | 10ms | -238ms | -96.06
| PluginStore.Get | p99 | 4.75s | 246ms | -4.504s | -94.82
| PreferenceStore.DeleteCategoryAndName | p99 | 233ms | 45ms | -188ms | -80.51
| JobStore.GetAllByTypePage | p99 | 2.2s | 482ms | -1.718s | -78.08
| RoleStore.ChannelHigherScopedPermissions | p99 | 2.172s | 499ms | -1.673s | -77.04
| UserStore.GetProfilesInChannel | p99 | 1.93s | 455ms | -1.475s | -76.43
| PostStore.GetPostReminders | p99 | 87ms | 21ms | -66ms | -75.43
| ThreadStore.Get | p99 | 2.188s | 867ms | -1.321s | -60.37
| UserStore.GetProfilesNotInChannel | p99 | 2.29s | 930ms | -1.36s | -59.39
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 233ms | 97ms | -136ms | -58.24
| TeamStore.GetActiveMemberCount | p99 | 2.29s | 991ms | -1.299s | -56.73
| StatusStore.UpdateExpiredDNDStatuses | p99 | 87ms | 43ms | -44ms | -50.57
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 1.945s | 987ms | -958ms | -49.26
| UserAccessTokenStore.GetByToken | p99 | 1.795s | 913ms | -882ms | -49.14
| PostPriorityStore.GetForPost | p99 | 1.743s | 901ms | -842ms | -48.32
| UserStore.GetAllProfilesInChannel | p99 | 7.35s | 3.822s | -3.528s | -48.00
| ChannelStore.GetChannelUnread | p99 | 1.823s | 970ms | -853ms | -46.78
| LinkMetadataStore.Save | p99 | 140ms | 75ms | -65ms | -46.27
| ChannelStore.AutocompleteInTeamForSearch | p99 | 4.48s | 2.462s | -2.018s | -45.05
| JobStore.GetNewestJobByStatusesAndType | p99 | 1.855s | 1.03s | -825ms | -44.47
| FileInfoStore.SetContent | p99 | 170ms | 95ms | -75ms | -44.25
| JobStore.GetCountByStatusAndType | p99 | 1.742s | 982ms | -760ms | -43.62
| ChannelStore.GetPublicChannelsForTeam | p99 | 1.69s | 982ms | -708ms | -41.89
| JobStore.UpdateStatusOptimistically | p99 | 146ms | 87ms | -59ms | -40.28
| PostPersistentNotificationStore.Get | p99 | 76ms | 46ms | -30ms | -39.22
| UserStore.AutocompleteUsersInChannel | p99 | 3.921s | 2.488s | -1.433s | -36.55
| ChannelStore.GetMemberCount | p99 | 3.591s | 2.348s | -1.243s | -34.61
| JobStore.Save | p99 | 89ms | 61ms | -28ms | -31.58
| ChannelStore.GetPinnedPostCount | p99 | 1.97s | 1.394s | -576ms | -29.24
| PostAcknowledgementStore.GetForPost | p99 | 998ms | 735ms | -263ms | -26.34
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 4.587s | 3.424s | -1.163s | -25.36
| ChannelStore.GetChannelsByUser | p99 | 1.312s | 991ms | -321ms | -24.47
| ChannelStore.SearchGroupChannels | p99 | 1.436s | 1.115s | -321ms | -22.35
| ChannelStore.GetSidebarCategory | p99 | 1.63s | 1.27s | -360ms | -22.09
| UserStore.GetUnreadCount | p99 | 1.511s | 1.181s | -330ms | -21.84
| StatusStore.GetByIds | p99 | 1.842s | 1.478s | -364ms | -19.76
| JobStore.Get | p99 | 2.397s | 1.93s | -467ms | -19.48
| ComplianceStore.MessageExport | p99 | 1.91s | 1.539s | -371ms | -19.42
| UserStore.Get | p99 | 925ms | 761ms | -164ms | -17.73
| ChannelStore.GetFileCount | p99 | 984ms | 816ms | -168ms | -17.07
| PostStore.SearchPostsForUser | p99 | 1.975s | 1.638s | -337ms | -17.06
| PreferenceStore.GetAll | p99 | 1.588s | 1.368s | -220ms | -13.85
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 1.503s | 1.298s | -205ms | -13.64
| PostStore.GetSingle | p99 | 1.815s | 1.576s | -239ms | -13.17
| JobStore.GetAllByStatus | p99 | 1.937s | 1.689s | -248ms | -12.80
| TeamStore.Get | p99 | 1.738s | 1.523s | -215ms | -12.37
| TeamStore.GetMember | p99 | 188ms | 166ms | -22ms | -11.69
| ChannelStore.GetAllChannelMembersForUser | p99 | 910ms | 805ms | -105ms | -11.54
| LinkMetadataStore.Get | p99 | 1.821s | 1.613s | -208ms | -11.42
| PostStore.GetEtag | p99 | 1.487s | 1.32s | -167ms | -11.23
| ChannelStore.GetChannels | p99 | 1.663s | 1.48s | -183ms | -11.01
| ThreadStore.GetMembershipForUser | p99 | 1.858s | 1.661s | -197ms | -10.60
| WebhookStore.GetOutgoingByTeam | p99 | 1.817s | 1.634s | -183ms | -10.07
| PostStore.GetPostsBefore | p99 | 1.56s | 1.404s | -156ms | -10.00
| PostStore.GetPostsAfter | p99 | 1.841s | 1.661s | -180ms | -9.78
| PostStore.GetPostsSince | p99 | 1.885s | 1.707s | -178ms | -9.44
| PreferenceStore.Get | p99 | 1.613s | 1.462s | -151ms | -9.36
| ChannelStore.GetMembersForUser | p99 | 1.617s | 1.476s | -141ms | -8.72
| ClusterDiscoveryStore.SetLastPingAt | p99 | 93ms | 85ms | -8ms | -8.57
| ThreadStore.GetThreadFollowers | p99 | 1.884s | 1.724s | -160ms | -8.49
| UserStore.Search | p99 | 2.328s | 2.146s | -182ms | -7.82
| ReactionStore.GetForPost | p99 | 1.725s | 1.593s | -132ms | -7.65
| PostStore.GetPostsByThread | p99 | 1.85s | 1.716s | -134ms | -7.24
| ChannelStore.GetMemberForPost | p99 | 1.92s | 1.787s | -133ms | -6.93
| DraftStore.Get | p99 | 2.005s | 1.874s | -131ms | -6.53
| ThreadStore.GetThreadsForUser | p99 | 1.856s | 1.747s | -109ms | -5.87
| PostPersistentNotificationStore.GetSingle | p99 | 1.674s | 1.578s | -96ms | -5.74
| UserStore.GetByUsername | p99 | 1.995s | 1.893s | -102ms | -5.11
| ChannelStore.Get | p99 | 1.844s | 1.75s | -94ms | -5.10
| BotStore.Get | p99 | 850ms | 810ms | -40ms | -4.71
| GroupStore.GetGroups | p99 | 1.726s | 1.645s | -81ms | -4.69
| ThreadStore.GetThreadForUser | p99 | 2.281s | 2.175s | -106ms | -4.65
| SessionStore.GetSessionsExpired | p99 | 492ms | 470ms | -22ms | -4.47
| ChannelStore.SaveMember | p99 | 3.395s | 3.256s | -139ms | -4.09
| ThreadStore.GetThreadUnreadReplyCount | p99 | 1.899s | 1.823s | -76ms | -4.00
| ThreadStore.GetTeamsUnreadForUser | p99 | 2.057s | 1.978s | -79ms | -3.84
| DraftStore.Delete | p99 | 80ms | 77ms | -3ms | -3.76
| PostStore.Get | p99 | 2.354s | 2.267s | -87ms | -3.70
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 996ms | 960ms | -36ms | -3.61
| GroupStore.GetByName | p99 | 733ms | 709ms | -24ms | -3.27
| TeamStore.GetTeamsForUser | p99 | 870ms | 842ms | -28ms | -3.22
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 67ms | 65ms | -2ms | -3.00
| FileInfoStore.Get | p99 | 969ms | 940ms | -29ms | -2.99
| ChannelStore.GetByName | p99 | 963ms | 935ms | -28ms | -2.91
| FileInfoStore.GetForPost | p99 | 1.843s | 1.793s | -50ms | -2.71
| UserStore.GetProfilesByUsernames | p99 | 995ms | 969ms | -26ms | -2.61
| FileInfoStore.AttachToPost | p99 | 89ms | 87ms | -2ms | -2.25
| PostPriorityStore.GetForPosts | p99 | 2.47s | 2.419s | -51ms | -2.07
| PostAcknowledgementStore.GetForPosts | p99 | 2.458s | 2.408s | -50ms | -2.03
| ChannelStore.CreateInitialSidebarCategories | p99 | 938ms | 919ms | -19ms | -2.02
| SessionStore.Get | p99 | 978ms | 959ms | -19ms | -1.94
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 987ms | 970ms | -17ms | -1.72
| ProductNoticesStore.GetViews | p99 | 247ms | 243ms | -4ms | -1.62
| DraftStore.GetDraftsForUser | p99 | 1.983s | 1.953s | -30ms | -1.51
| PostStore.GetPosts | p99 | 888ms | 875ms | -13ms | -1.46
| TeamStore.GetTeamsByUserId | p99 | 969ms | 959ms | -10ms | -1.03
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getClientLicense | avg | 0s | 63ms | 63ms | 32711.10
| getGroupsAssociatedToChannelsByTeam | avg | 3ms | 726ms | 723ms | 27007.62
| getGroups | avg | 51ms | 282ms | 231ms | 450.21
| getProductNotices | avg | 10ms | 32ms | 22ms | 218.61
| getPrevTrialLicense | avg | 38ms | 82ms | 44ms | 115.06
| createCategoryForTeamForUser | avg | 148ms | 296ms | 148ms | 100.09
| login | avg | 472ms | 730ms | 258ms | 54.63
| getChannelMembersForUser | avg | 124ms | 174ms | 50ms | 40.41
| createDirectChannel | avg | 1.186s | 1.233s | 47ms | 3.96
| createUser | avg | 376ms | 390ms | 14ms | 3.72
| getUsers | avg | 58ms | 60ms | 2ms | 3.44
| getUser | avg | 162ms | 167ms | 5ms | 3.08
| getAllTeams | avg | 130ms | 134ms | 4ms | 3.07
| addChannelMember | avg | 2.249s | 2.307s | 58ms | 2.58
| getDrafts | avg | 200ms | 203ms | 3ms | 1.50
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 2.47s | 2.465s | 49759.84
| getClientLicense | p99 | 5ms | 2.261s | 2.256s | 45568.06
| getGroups | p99 | 100ms | 2.41s | 2.31s | 2321.61
| getProductNotices | p99 | 25ms | 244ms | 219ms | 880.88
| getChannelMembersForUser | p99 | 248ms | 2.335s | 2.087s | 841.53
| getPrevTrialLicense | p99 | 99ms | 915ms | 816ms | 824.24
| createCategoryForTeamForUser | p99 | 249ms | 495ms | 246ms | 98.99
| getChannel | p99 | 3.108s | 3.95s | 842ms | 27.09
| login | p99 | 3.27s | 4.12s | 850ms | 26.00
| getUserStatusesByIds | p99 | 12ms | 15ms | 3ms | 24.10
| patchPost | p99 | 9.225s | 10s | 775ms | 8.40
| deletePost | p99 | 2.335s | 2.425s | 90ms | 3.85
| getDrafts | p99 | 1.984s | 2.03s | 46ms | 2.32
| getUsers | p99 | 797ms | 811ms | 14ms | 1.76
| uploadFileStream | p99 | 1.519s | 1.545s | 26ms | 1.71
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 2ms | 0s | -2ms | -102.37
| getChannelMembers | avg | 99ms | 0s | -99ms | -100.01
| saveReaction | avg | 528ms | 0s | -528ms | -100.00
| getRolesByNames | avg | 167ms | 27ms | -140ms | -83.66
| getJobsByType | avg | 246ms | 96ms | -150ms | -61.09
| unfollowThreadByUser | avg | 562ms | 276ms | -286ms | -50.87
| logout | avg | 467ms | 286ms | -181ms | -38.77
| followThreadByUser | avg | 543ms | 345ms | -198ms | -36.48
| getChannelUnread | avg | 202ms | 145ms | -57ms | -28.16
| createChannel | avg | 2.833s | 2.086s | -747ms | -26.37
| autocompleteChannelsForTeamForSearch | avg | 670ms | 508ms | -162ms | -24.19
| deletePost | avg | 557ms | 453ms | -104ms | -18.67
| getAnalytics | avg | 1.138s | 942ms | -196ms | -17.23
| updateCategoriesForTeamForUser | avg | 1.03s | 863ms | -167ms | -16.22
| getChannelStats | avg | 142ms | 119ms | -23ms | -16.21
| createPost | avg | 4.022s | 3.374s | -648ms | -16.11
| searchGroupChannels | avg | 192ms | 165ms | -27ms | -14.07
| getPublicChannelsForTeam | avg | 216ms | 187ms | -29ms | -13.41
| setPostReminder | avg | 774ms | 673ms | -101ms | -13.04
| searchPostsInTeam | avg | 623ms | 546ms | -77ms | -12.36
| getPostsForChannel | avg | 1.823s | 1.603s | -220ms | -12.07
| getPostThread | avg | 1.019s | 909ms | -110ms | -10.80
| createGroupChannel | avg | 2.885s | 2.592s | -293ms | -10.15
| updateReadStateThreadByUser | avg | 1.363s | 1.242s | -121ms | -8.88
| getChannelsForUser | avg | 149ms | 136ms | -13ms | -8.75
| getTeamStats | avg | 770ms | 703ms | -67ms | -8.70
| getFilePreview | avg | 190ms | 174ms | -16ms | -8.43
| deleteDraft | avg | 207ms | 190ms | -17ms | -8.23
| getUsersByNames | avg | 134ms | 123ms | -11ms | -8.22
| getFileThumbnail | avg | 187ms | 172ms | -15ms | -8.02
| patchPost | avg | 1.968s | 1.813s | -155ms | -7.87
| viewChannel | avg | 339ms | 313ms | -26ms | -7.68
| autocompleteUsers | avg | 691ms | 638ms | -53ms | -7.66
| removeUserCustomStatus | avg | 293ms | 274ms | -19ms | -6.48
| getChannelsForTeamForUser | avg | 173ms | 163ms | -10ms | -5.80
| searchAllChannels | avg | 4s | 3.77s | -230ms | -5.75
| getChannelMember | avg | 175ms | 165ms | -10ms | -5.73
| getProfileImage | avg | 92ms | 87ms | -5ms | -5.45
| searchUsers | avg | 414ms | 393ms | -21ms | -5.08
| getChannelMembersForTeamForUser | avg | 163ms | 155ms | -8ms | -4.90
| getThreadsForUser | avg | 195ms | 188ms | -7ms | -3.60
| getTeamMembersForUser | avg | 105ms | 102ms | -3ms | -2.85
| getFilteredUsersStats | avg | 215ms | 210ms | -5ms | -2.32
| getTeamsUnreadForUser | avg | 209ms | 205ms | -4ms | -1.92
| uploadFileStream | avg | 416ms | 411ms | -5ms | -1.20
| getChannel | avg | 485ms | 480ms | -5ms | -1.03
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| updateUserCustomStatus | p99 | 5ms | 0s | -5ms | -100.27
| getChannelMembers | p99 | 248ms | 0s | -248ms | -100.19
| saveReaction | p99 | 3.795s | 0s | -3.795s | -99.99
| getRolesByNames | p99 | 2.335s | 241ms | -2.094s | -89.68
| followThreadByUser | p99 | 4.525s | 981ms | -3.544s | -78.32
| getJobsByType | p99 | 2.2s | 482ms | -1.718s | -78.08
| setPostReminder | p99 | 8.65s | 2.438s | -6.212s | -71.81
| unfollowThreadByUser | p99 | 5.851s | 1.69s | -4.161s | -71.12
| removeUserCustomStatus | p99 | 2.5s | 960ms | -1.54s | -61.59
| logout | p99 | 2.335s | 962ms | -1.373s | -58.80
| autocompleteChannelsForTeamForSearch | p99 | 4.48s | 2.462s | -2.018s | -45.05
| getPublicChannelsForTeam | p99 | 1.69s | 982ms | -708ms | -41.89
| getTeamMember | p99 | 390ms | 244ms | -146ms | -37.46
| autocompleteUsers | p99 | 3.699s | 2.473s | -1.226s | -33.14
| getChannelUnread | p99 | 1.934s | 1.335s | -599ms | -30.98
| getPostThread | p99 | 6.633s | 4.905s | -1.728s | -26.05
| getChannelsForUser | p99 | 1.318s | 992ms | -326ms | -24.74
| searchGroupChannels | p99 | 1.436s | 1.115s | -321ms | -22.35
| updateCategoriesForTeamForUser | p99 | 4.587s | 3.9s | -687ms | -14.98
| updateReadStateThreadByUser | p99 | 8.226s | 7.098s | -1.128s | -13.71
| searchPostsInTeam | p99 | 6.942s | 5.991s | -951ms | -13.70
| getPreferences | p99 | 1.618s | 1.426s | -192ms | -11.87
| getChannelsForTeamForUser | p99 | 1.689s | 1.505s | -184ms | -10.89
| getFilePreview | p99 | 1.493s | 1.335s | -158ms | -10.58
| getFileThumbnail | p99 | 1.609s | 1.464s | -145ms | -9.01
| getChannelMembersForTeamForUser | p99 | 1.627s | 1.485s | -142ms | -8.73
| getChannelStats | p99 | 2.218s | 2.054s | -164ms | -7.40
| searchUsers | p99 | 2.341s | 2.168s | -173ms | -7.39
| deleteDraft | p99 | 2.007s | 1.875s | -132ms | -6.58
| getChannelMember | p99 | 1.862s | 1.742s | -120ms | -6.44
| addChannelMember | p99 | 9.895s | 9.477s | -418ms | -4.22
| createChannel | p99 | 9.6s | 9.25s | -350ms | -3.65
| getThreadsForUser | p99 | 2.059s | 1.991s | -68ms | -3.30
| getUsersByNames | p99 | 1.009s | 976ms | -33ms | -3.27
| getPostsForChannelAroundLastUnread | p99 | 4.479s | 4.349s | -130ms | -2.90
| getUsersByIds | p99 | 343ms | 335ms | -8ms | -2.33
| viewChannel | p99 | 2.422s | 2.37s | -52ms | -2.15
| getProfileImage | p99 | 482ms | 472ms | -10ms | -2.07
| getUser | p99 | 1.465s | 1.444s | -21ms | -1.43
| getTeamsUnreadForUser | p99 | 2.208s | 2.18s | -28ms | -1.27
| updatePreferences | p99 | 244ms | 241ms | -3ms | -1.23
| getTeamsForUser | p99 | 971ms | 960ms | -11ms | -1.13
| getAnalytics | p99 | 2.485s | 2.458s | -27ms | -1.09
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 75ms| 78ms | 3ms | 3.990
| BotStore.Get |  Avg| 187ms| 117ms | -70ms | -37.456
| |  P99| 850ms| 810ms | -40ms | -4.706
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 1.02s| 867ms | -153ms | -15.004
| |  P99| 4.587s| 3.424s | -1.163s | -25.355
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 63ms| 65ms | 2ms | 3.176
| ChannelStore.AnalyticsTypeCount |  Avg| 81ms| 129ms | 48ms | 59.576
| |  P99| 245ms| 910ms | 665ms | 270.876
| ChannelStore.Autocomplete |  Avg| 3.994s| 3.764s | -230ms | -5.758
| |  P99| 10s| 10s | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 670ms| 508ms | -162ms | -24.192
| |  P99| 4.48s| 2.462s | -2.018s | -45.049
| ChannelStore.CreateDirectChannel |  Avg| 522ms| 541ms | 19ms | 3.639
| |  P99| 3.113s| 4.025s | 912ms | 29.299
| ChannelStore.CreateInitialSidebarCategories |  Avg| 122ms| 125ms | 3ms | 2.467
| |  P99| 938ms| 919ms | -19ms | -2.025
| ChannelStore.CreateSidebarCategory |  Avg| 19ms| 155ms | 136ms | 713.790
| |  P99| 25ms| 495ms | 470ms | 1891.348
| ChannelStore.Get |  Avg| 199ms| 197ms | -2ms | -1.006
| |  P99| 1.844s| 1.75s | -94ms | -5.099
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 168ms| 166ms | -2ms | -1.189
| |  P99| 996ms| 960ms | -36ms | -3.614
| ChannelStore.GetAllChannelMembersForUser |  Avg| 97ms| 86ms | -11ms | -11.311
| |  P99| 910ms| 805ms | -105ms | -11.542
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 199ms| 167ms | -32ms | -16.049
| |  P99| 1.945s| 987ms | -958ms | -49.256
| ChannelStore.GetByName |  Avg| 109ms| 113ms | 4ms | 3.654
| |  P99| 963ms| 935ms | -28ms | -2.906
| ChannelStore.GetByNameIncludeDeleted |  Avg| 75ms| 0s | -75ms | -99.375
| |  P99| 100ms| 0s | -100ms | -100.451
| ChannelStore.GetChannelUnread |  Avg| 188ms| 133ms | -55ms | -29.295
| |  P99| 1.823s| 970ms | -853ms | -46.779
| ChannelStore.GetChannels |  Avg| 168ms| 158ms | -10ms | -5.945
| |  P99| 1.663s| 1.48s | -183ms | -11.005
| ChannelStore.GetChannelsByIds |  Avg| 187ms| 0s | -187ms | -99.778
| |  P99| 492ms| 0s | -492ms | -99.899
| ChannelStore.GetChannelsByUser |  Avg| 148ms| 136ms | -12ms | -8.124
| |  P99| 1.312s| 991ms | -321ms | -24.470
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 152ms| 140ms | -12ms | -7.880
| |  P99| 1.503s| 1.298s | -205ms | -13.640
| ChannelStore.GetFileCount |  Avg| 125ms| 99ms | -26ms | -20.770
| |  P99| 984ms| 816ms | -168ms | -17.069
| ChannelStore.GetGuestCount |  Avg| 148ms| 151ms | 3ms | 2.033
| |  P99| 1.226s| 1.276s | 50ms | 4.079
| ChannelStore.GetMember |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 193ms| 199ms | 6ms | 3.117
| ChannelStore.GetMemberCount |  Avg| 557ms| 516ms | -41ms | -7.361
| |  P99| 3.591s| 2.348s | -1.243s | -34.611
| ChannelStore.GetMemberCountsByGroup |  Avg| 1ms| 0s | -1ms | -80.767
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMemberForPost |  Avg| 198ms| 184ms | -14ms | -7.084
| |  P99| 1.92s| 1.787s | -133ms | -6.925
| ChannelStore.GetMemberLastViewedAt |  Avg| 102ms| 104ms | 2ms | 1.958
| |  P99| 918ms| 915ms | -3ms | -0.327
| ChannelStore.GetMembers |  Avg| 98ms| 0s | -98ms | -100.095
| |  P99| 246ms| 0s | -246ms | -99.881
| ChannelStore.GetMembersForUser |  Avg| 162ms| 154ms | -8ms | -4.946
| |  P99| 1.617s| 1.476s | -141ms | -8.722
| ChannelStore.GetMembersForUserWithPagination |  Avg| 159ms| 152ms | -7ms | -4.415
| |  P99| 947ms| 2.095s | 1.148s | 121.163
| ChannelStore.GetPinnedPostCount |  Avg| 180ms| 152ms | -28ms | -15.541
| |  P99| 1.97s| 1.394s | -576ms | -29.238
| ChannelStore.GetPublicChannelsForTeam |  Avg| 215ms| 186ms | -29ms | -13.506
| |  P99| 1.69s| 982ms | -708ms | -41.887
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 290ms| 288ms | -2ms | -0.689
| |  P99| 2.328s| 2.336s | 8ms | 0.344
| ChannelStore.GetSidebarCategory |  Avg| 221ms| 175ms | -46ms | -20.861
| |  P99| 1.63s| 1.27s | -360ms | -22.087
| ChannelStore.GetTeamChannels |  Avg| 268ms| 209ms | -59ms | -22.004
| |  P99| 920ms| 925ms | 5ms | 0.543
| ChannelStore.IncrementMentionCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 65ms| 64ms | -1ms | -1.542
| ChannelStore.Save |  Avg| 235ms| 197ms | -38ms | -16.155
| |  P99| 1.84s| 1.9s | 60ms | 3.260
| ChannelStore.SaveMember |  Avg| 470ms| 480ms | 10ms | 2.126
| |  P99| 3.395s| 3.256s | -139ms | -4.095
| ChannelStore.SearchGroupChannels |  Avg| 192ms| 165ms | -27ms | -14.077
| |  P99| 1.436s| 1.115s | -321ms | -22.349
| ChannelStore.UpdateLastViewedAt |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 156ms| 160ms | 4ms | 2.558
| ChannelStore.UpdateSidebarCategories |  Avg| 394ms| 361ms | -33ms | -8.385
| |  P99| 2.005s| 2.28s | 275ms | 13.716
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 67ms| 65ms | -2ms | -3.003
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 8ms| 7ms | -1ms | -12.353
| |  P99| 93ms| 85ms | -8ms | -8.565
| CommandWebhookStore.Cleanup |  Avg| 3ms| 18ms | 15ms | 543.935
| |  P99| 10ms| 49ms | 39ms | 397.959
| ComplianceStore.MessageExport |  Avg| 186ms| 144ms | -42ms | -22.548
| |  P99| 1.91s| 1.539s | -371ms | -19.424
| DraftStore.Delete |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 77ms | -3ms | -3.763
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 43ms| 31ms | -12ms | -27.802
| |  P99| 233ms| 97ms | -136ms | -58.244
| DraftStore.Get |  Avg| 206ms| 190ms | -16ms | -7.768
| |  P99| 2.005s| 1.874s | -131ms | -6.533
| DraftStore.GetDraftsForUser |  Avg| 195ms| 195ms | 0s | 0.000
| |  P99| 1.983s| 1.953s | -30ms | -1.513
| DraftStore.Upsert |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 85ms| 86ms | 1ms | 1.171
| EmojiStore.GetByName |  Avg| 164ms| 163ms | -1ms | -0.611
| |  P99| 1.56s| 1.562s | 2ms | 0.128
| EmojiStore.GetMultipleByName |  Avg| 111ms| 284ms | 173ms | 156.309
| |  P99| 452ms| 960ms | 508ms | 112.268
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 87ms | -2ms | -2.255
| FileInfoStore.Get |  Avg| 121ms| 108ms | -13ms | -10.741
| |  P99| 969ms| 940ms | -29ms | -2.992
| FileInfoStore.GetByIds |  Avg| 172ms| 174ms | 2ms | 1.164
| |  P99| 966ms| 1.695s | 729ms | 75.437
| FileInfoStore.GetForPost |  Avg| 183ms| 178ms | -5ms | -2.726
| |  P99| 1.843s| 1.793s | -50ms | -2.713
| FileInfoStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 13ms| 11ms | -2ms | -15.850
| |  P99| 170ms| 95ms | -75ms | -44.247
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 109ms| 115ms | 6ms | 5.512
| |  P99| 929ms| 929ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 82ms| 83ms | 1ms | 1.213
| |  P99| 733ms| 709ms | -24ms | -3.274
| GroupStore.GetGroups |  Avg| 167ms| 158ms | -9ms | -5.386
| |  P99| 1.726s| 1.645s | -81ms | -4.692
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 30ms| 366ms | 336ms | 1128.041
| |  P99| 99ms| 2.44s | 2.341s | 2364.646
| JobStore.Get |  Avg| 234ms| 188ms | -46ms | -19.674
| |  P99| 2.397s| 1.93s | -467ms | -19.483
| JobStore.GetAllByStatus |  Avg| 171ms| 156ms | -15ms | -8.771
| |  P99| 1.937s| 1.689s | -248ms | -12.802
| JobStore.GetAllByTypePage |  Avg| 245ms| 96ms | -149ms | -60.733
| |  P99| 2.2s| 482ms | -1.718s | -78.085
| JobStore.GetCountByStatusAndType |  Avg| 217ms| 101ms | -116ms | -53.547
| |  P99| 1.742s| 982ms | -760ms | -43.615
| JobStore.GetNewestJobByStatusesAndType |  Avg| 174ms| 116ms | -58ms | -33.340
| |  P99| 1.855s| 1.03s | -825ms | -44.474
| JobStore.Save |  Avg| 7ms| 5ms | -2ms | -28.394
| |  P99| 89ms| 61ms | -28ms | -31.579
| JobStore.UpdateOptimistically |  Avg| 8ms| 9ms | 1ms | 11.843
| |  P99| 92ms| 97ms | 5ms | 5.431
| JobStore.UpdateStatus |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 60ms | 13ms | 27.897
| JobStore.UpdateStatusOptimistically |  Avg| 10ms| 7ms | -3ms | -31.344
| |  P99| 146ms| 87ms | -59ms | -40.276
| LicenseStore.GetAll |  Avg| 125ms| 85ms | -40ms | -31.918
| |  P99| 488ms| 910ms | 422ms | 86.563
| LinkMetadataStore.Get |  Avg| 174ms| 157ms | -17ms | -9.783
| |  P99| 1.821s| 1.613s | -208ms | -11.424
| LinkMetadataStore.Save |  Avg| 11ms| 5ms | -6ms | -54.222
| |  P99| 140ms| 75ms | -65ms | -46.267
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| PluginStore.Get |  Avg| 495ms| 83ms | -412ms | -83.261
| |  P99| 4.75s| 246ms | -4.504s | -94.821
| PluginStore.List |  Avg| 132ms| 144ms | 12ms | 9.067
| |  P99| 870ms| 1.6s | 730ms | 83.908
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 95ms| 94ms | -1ms | -1.057
| PostAcknowledgementStore.GetForPost |  Avg| 164ms| 108ms | -56ms | -34.071
| |  P99| 998ms| 735ms | -263ms | -26.344
| PostAcknowledgementStore.GetForPosts |  Avg| 270ms| 252ms | -18ms | -6.668
| |  P99| 2.458s| 2.408s | -50ms | -2.034
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 4ms | 1ms | 28.998
| |  P99| 45ms| 46ms | 1ms | 2.228
| PostPersistentNotificationStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 76ms| 46ms | -30ms | -39.216
| PostPersistentNotificationStore.GetSingle |  Avg| 176ms| 170ms | -6ms | -3.414
| |  P99| 1.674s| 1.578s | -96ms | -5.736
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 2ms| 0s | -2ms | -81.662
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 146ms| 125ms | -21ms | -14.336
| |  P99| 1.743s| 901ms | -842ms | -48.319
| PostPriorityStore.GetForPosts |  Avg| 278ms| 259ms | -19ms | -6.843
| |  P99| 2.47s| 2.419s | -51ms | -2.065
| PostStore.AnalyticsPostCount |  Avg| 1.367s| 1.905s | 538ms | 39.363
| |  P99| 4.95s| 4.95s | 0s | 0.000
| PostStore.Delete |  Avg| 116ms| 135ms | 19ms | 16.422
| |  P99| 247ms| 900ms | 653ms | 264.694
| PostStore.Get |  Avg| 295ms| 267ms | -28ms | -9.486
| |  P99| 2.354s| 2.267s | -87ms | -3.696
| PostStore.GetEtag |  Avg| 159ms| 153ms | -6ms | -3.776
| |  P99| 1.487s| 1.32s | -167ms | -11.229
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 68ms| 69ms | 1ms | 1.478
| PostStore.GetPostIdBeforeTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 81ms| 82ms | 1ms | 1.242
| PostStore.GetPostReminderMetadata |  Avg| 185ms| 169ms | -16ms | -8.645
| |  P99| 1.765s| 1.765s | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 11ms| 4ms | -7ms | -63.095
| |  P99| 87ms| 21ms | -66ms | -75.429
| PostStore.GetPosts |  Avg| 102ms| 103ms | 1ms | 0.978
| |  P99| 888ms| 875ms | -13ms | -1.463
| PostStore.GetPostsAfter |  Avg| 177ms| 131ms | -46ms | -25.943
| |  P99| 1.841s| 1.661s | -180ms | -9.775
| PostStore.GetPostsBefore |  Avg| 165ms| 154ms | -11ms | -6.660
| |  P99| 1.56s| 1.404s | -156ms | -10.003
| PostStore.GetPostsByIds |  Avg| 112ms| 0s | -112ms | -99.969
| |  P99| 247ms| 0s | -247ms | -99.932
| PostStore.GetPostsByThread |  Avg| 179ms| 166ms | -13ms | -7.258
| |  P99| 1.85s| 1.716s | -134ms | -7.244
| PostStore.GetPostsSince |  Avg| 217ms| 202ms | -15ms | -6.903
| |  P99| 1.885s| 1.707s | -178ms | -9.443
| PostStore.GetSingle |  Avg| 172ms| 154ms | -18ms | -10.485
| |  P99| 1.815s| 1.576s | -239ms | -13.171
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 18ms| 19ms | 1ms | 5.494
| |  P99| 222ms| 222ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 251ms| 211ms | -40ms | -15.965
| |  P99| 1.975s| 1.638s | -337ms | -17.063
| PostStore.SetPostReminder |  Avg| 12ms| 15ms | 3ms | 25.571
| |  P99| 209ms| 213ms | 4ms | 1.909
| PostStore.Update |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 215ms| 237ms | 22ms | 10.229
| PreferenceStore.DeleteCategoryAndName |  Avg| 22ms| 6ms | -16ms | -74.001
| |  P99| 233ms| 45ms | -188ms | -80.514
| PreferenceStore.Get |  Avg| 162ms| 150ms | -12ms | -7.387
| |  P99| 1.613s| 1.462s | -151ms | -9.360
| PreferenceStore.GetAll |  Avg| 172ms| 173ms | 1ms | 0.580
| |  P99| 1.588s| 1.368s | -220ms | -13.851
| PreferenceStore.Save |  Avg| 14ms| 15ms | 1ms | 7.273
| |  P99| 201ms| 210ms | 9ms | 4.470
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 59ms| 26ms | -33ms | -55.549
| |  P99| 247ms| 243ms | -4ms | -1.619
| ProductNoticesStore.View |  Avg| 37ms| 40ms | 3ms | 8.109
| |  P99| 394ms| 434ms | 40ms | 10.145
| ReactionStore.GetForPost |  Avg| 179ms| 158ms | -21ms | -11.699
| |  P99| 1.725s| 1.593s | -132ms | -7.653
| RetentionPolicyStore.GetAll |  Avg| 177ms| 3ms | -174ms | -98.323
| |  P99| 248ms| 10ms | -238ms | -96.065
| RetentionPolicyStore.GetCount |  Avg| 190ms| 1ms | -189ms | -99.263
| |  P99| 493ms| 5ms | -488ms | -99.086
| RoleStore.ChannelHigherScopedPermissions |  Avg| 187ms| 113ms | -74ms | -39.535
| |  P99| 2.172s| 499ms | -1.673s | -77.038
| RoleStore.GetByNames |  Avg| 0s| 147ms | 147ms | 2395657.166
| |  P99| 5ms| 857ms | 852ms | 17211.653
| SessionStore.Get |  Avg| 122ms| 122ms | 0s | 0.000
| |  P99| 978ms| 959ms | -19ms | -1.943
| SessionStore.GetLRUSessions |  Avg| 116ms| 117ms | 1ms | 0.859
| |  P99| 951ms| 953ms | 2ms | 0.210
| SessionStore.GetSessionsExpired |  Avg| 168ms| 68ms | -100ms | -59.461
| |  P99| 492ms| 470ms | -22ms | -4.475
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 134ms| 123ms | -11ms | -8.191
| |  P99| 1.08s| 1.332s | 252ms | 23.329
| SessionStore.Remove |  Avg| 12ms| 7ms | -5ms | -41.569
| |  P99| 88ms| 88ms | 0s | 0.000
| SessionStore.Save |  Avg| 117ms| 118ms | 1ms | 0.852
| |  P99| 938ms| 935ms | -3ms | -0.320
| SessionStore.UpdateLastActivityAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 71ms| 70ms | -1ms | -1.399
| StatusStore.Get |  Avg| 72ms| 78ms | 6ms | 8.374
| |  P99| 665ms| 786ms | 121ms | 18.191
| StatusStore.GetByIds |  Avg| 192ms| 169ms | -23ms | -11.978
| |  P99| 1.842s| 1.478s | -364ms | -19.759
| StatusStore.SaveOrUpdate |  Avg| 10ms| 30ms | 20ms | 201.609
| |  P99| 142ms| 458ms | 316ms | 222.861
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 6ms | -3ms | -35.062
| |  P99| 87ms| 43ms | -44ms | -50.575
| StatusStore.UpdateLastActivityAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 85ms| 88ms | 3ms | 3.534
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 54ms| 56ms | 2ms | 3.695
| TeamStore.AnalyticsTeamCount |  Avg| 71ms| 88ms | 17ms | 24.098
| |  P99| 245ms| 478ms | 233ms | 94.909
| TeamStore.Get |  Avg| 165ms| 150ms | -15ms | -9.101
| |  P99| 1.738s| 1.523s | -215ms | -12.368
| TeamStore.GetActiveMemberCount |  Avg| 613ms| 521ms | -92ms | -15.010
| |  P99| 2.29s| 991ms | -1.299s | -56.726
| TeamStore.GetAllPage |  Avg| 122ms| 125ms | 3ms | 2.459
| |  P99| 962ms| 959ms | -3ms | -0.312
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 124ms| 123ms | -1ms | -0.809
| |  P99| 987ms| 970ms | -17ms | -1.722
| TeamStore.GetMany |  Avg| 159ms| 0s | -159ms | -100.109
| |  P99| 492ms| 0s | -492ms | -99.899
| TeamStore.GetMember |  Avg| 7ms| 6ms | -1ms | -13.501
| |  P99| 188ms| 166ms | -22ms | -11.691
| TeamStore.GetTeamsByUserId |  Avg| 127ms| 128ms | 1ms | 0.789
| |  P99| 969ms| 959ms | -10ms | -1.032
| TeamStore.GetTeamsForUser |  Avg| 96ms| 94ms | -2ms | -2.088
| |  P99| 870ms| 842ms | -28ms | -3.219
| TeamStore.GetTotalMemberCount |  Avg| 659ms| 585ms | -74ms | -11.222
| |  P99| 2.395s| 2.395s | 0s | 0.000
| TeamStore.SaveMember |  Avg| 215ms| 220ms | 5ms | 2.327
| |  P99| 992ms| 984ms | -8ms | -0.806
| ThreadStore.Get |  Avg| 254ms| 123ms | -131ms | -51.593
| |  P99| 2.188s| 867ms | -1.321s | -60.375
| ThreadStore.GetMembershipForUser |  Avg| 170ms| 160ms | -10ms | -5.871
| |  P99| 1.858s| 1.661s | -197ms | -10.605
| ThreadStore.GetTeamsUnreadForUser |  Avg| 173ms| 165ms | -8ms | -4.621
| |  P99| 2.057s| 1.978s | -79ms | -3.841
| ThreadStore.GetThreadFollowers |  Avg| 175ms| 167ms | -8ms | -4.571
| |  P99| 1.884s| 1.724s | -160ms | -8.491
| ThreadStore.GetThreadForUser |  Avg| 259ms| 239ms | -20ms | -7.719
| |  P99| 2.281s| 2.175s | -106ms | -4.647
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 192ms| 174ms | -18ms | -9.381
| |  P99| 1.899s| 1.823s | -76ms | -4.001
| ThreadStore.GetThreadsForUser |  Avg| 189ms| 180ms | -9ms | -4.773
| |  P99| 1.856s| 1.747s | -109ms | -5.873
| ThreadStore.GetTotalThreads |  Avg| 121ms| 123ms | 2ms | 1.658
| |  P99| 1s| 990ms | -10ms | -1.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 124ms| 123ms | -1ms | -0.808
| |  P99| 988ms| 1.001s | 13ms | 1.316
| ThreadStore.GetTotalUnreadThreads |  Avg| 122ms| 122ms | 0s | 0.000
| |  P99| 975ms| 977ms | 2ms | 0.205
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 122ms| 122ms | 0s | 0.000
| |  P99| 985ms| 977ms | -8ms | -0.813
| ThreadStore.MaintainMembership |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 189ms| 191ms | 2ms | 1.057
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 8ms | 1ms | 13.603
| |  P99| 92ms| 92ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 0s | -2ms | -108.840
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 79ms | -1ms | -1.250
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 92ms | 4ms | 4.554
| TokenStore.Cleanup |  Avg| 2ms| 19ms | 17ms | 767.364
| |  P99| 10ms| 49ms | 39ms | 397.959
| UserAccessTokenStore.GetByToken |  Avg| 113ms| 137ms | 24ms | 21.167
| |  P99| 1.795s| 913ms | -882ms | -49.139
| UserStore.AnalyticsActiveCount |  Avg| 588ms| 607ms | 19ms | 3.231
| |  P99| 994ms| 2.23s | 1.236s | 124.346
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 48ms| 37ms | -11ms | -22.952
| |  P99| 98ms| 238ms | 140ms | 142.132
| UserStore.AutocompleteUsersInChannel |  Avg| 766ms| 722ms | -44ms | -5.745
| |  P99| 3.921s| 2.488s | -1.433s | -36.547
| UserStore.Count |  Avg| 315ms| 375ms | 60ms | 19.026
| |  P99| 975ms| 982ms | 7ms | 0.718
| UserStore.Get |  Avg| 78ms| 53ms | -25ms | -32.180
| |  P99| 925ms| 761ms | -164ms | -17.730
| UserStore.GetAllProfiles |  Avg| 95ms| 99ms | 4ms | 4.190
| |  P99| 915ms| 945ms | 30ms | 3.278
| UserStore.GetAllProfilesInChannel |  Avg| 1.251s| 1.196s | -55ms | -4.398
| |  P99| 7.35s| 3.822s | -3.528s | -48.001
| UserStore.GetByUsername |  Avg| 171ms| 161ms | -10ms | -5.847
| |  P99| 1.995s| 1.893s | -102ms | -5.113
| UserStore.GetForLogin |  Avg| 106ms| 106ms | 0s | 0.000
| |  P99| 888ms| 893ms | 5ms | 0.563
| UserStore.GetMany |  Avg| 118ms| 176ms | 58ms | 49.111
| |  P99| 890ms| 2.17s | 1.28s | 143.816
| UserStore.GetProfileByIds |  Avg| 94ms| 93ms | -1ms | -1.067
| |  P99| 963ms| 974ms | 11ms | 1.142
| UserStore.GetProfilesByUsernames |  Avg| 132ms| 121ms | -11ms | -8.340
| |  P99| 995ms| 969ms | -26ms | -2.613
| UserStore.GetProfilesInChannel |  Avg| 103ms| 111ms | 8ms | 7.787
| |  P99| 1.93s| 455ms | -1.475s | -76.429
| UserStore.GetProfilesNotInChannel |  Avg| 276ms| 163ms | -113ms | -40.917
| |  P99| 2.29s| 930ms | -1.36s | -59.388
| UserStore.GetUnreadCount |  Avg| 145ms| 130ms | -15ms | -10.338
| |  P99| 1.511s| 1.181s | -330ms | -21.841
| UserStore.IsEmpty |  Avg| 59ms| 61ms | 2ms | 3.402
| |  P99| 570ms| 668ms | 98ms | 17.203
| UserStore.Save |  Avg| 81ms| 81ms | 0s | 0.000
| |  P99| 316ms| 315ms | -1ms | -0.317
| UserStore.Search |  Avg| 409ms| 388ms | -21ms | -5.134
| |  P99| 2.328s| 2.146s | -182ms | -7.818
| UserStore.Update |  Avg| 9ms| 11ms | 2ms | 22.432
| |  P99| 100ms| 185ms | 85ms | 85.211
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 74ms| 77ms | 3ms | 4.042
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 72ms | 3ms | 4.346
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 58ms| 67ms | 9ms | 15.431
| UserTermsOfServiceStore.GetByUser |  Avg| 138ms| 140ms | 2ms | 1.449
| |  P99| 1.048s| 1.058s | 10ms | 0.954
| WebhookStore.GetOutgoingByTeam |  Avg| 177ms| 165ms | -12ms | -6.795
| |  P99| 1.817s| 1.634s | -183ms | -10.069
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 2.249s| 2.307s | 58ms | 2.579
| | P99| 9.895s| 9.477s | -418ms | -4.224
| addTeamMember | Avg| 3.752s| 3.716s | -36ms | -0.960
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 670ms| 508ms | -162ms | -24.188
| | P99| 4.48s| 2.462s | -2.018s | -45.049
| autocompleteUsers | Avg| 691ms| 638ms | -53ms | -7.665
| | P99| 3.699s| 2.473s | -1.226s | -33.144
| channelMemberCountsByGroup | Avg| 1ms| 0s | -1ms | -66.962
| | P99| 5ms| 0s | -5ms | -101.010
| createCategoryForTeamForUser | Avg| 148ms| 296ms | 148ms | 100.093
| | P99| 249ms| 495ms | 246ms | 98.994
| createChannel | Avg| 2.833s| 2.086s | -747ms | -26.366
| | P99| 9.6s| 9.25s | -350ms | -3.646
| createDirectChannel | Avg| 1.186s| 1.233s | 47ms | 3.961
| | P99| 4.93s| 4.908s | -22ms | -0.446
| createGroupChannel | Avg| 2.885s| 2.592s | -293ms | -10.155
| | P99| 10s| 10s | 0s | 0.000
| createPost | Avg| 4.022s| 3.374s | -648ms | -16.112
| | P99| 10s| 10s | 0s | 0.000
| createUser | Avg| 376ms| 390ms | 14ms | 3.724
| | P99| 2.306s| 2.326s | 20ms | 0.867
| deleteDraft | Avg| 207ms| 190ms | -17ms | -8.231
| | P99| 2.007s| 1.875s | -132ms | -6.578
| deletePost | Avg| 557ms| 453ms | -104ms | -18.667
| | P99| 2.335s| 2.425s | 90ms | 3.854
| followThreadByUser | Avg| 543ms| 345ms | -198ms | -36.477
| | P99| 4.525s| 981ms | -3.544s | -78.321
| getAllTeams | Avg| 130ms| 134ms | 4ms | 3.074
| | P99| 989ms| 986ms | -3ms | -0.303
| getAnalytics | Avg| 1.138s| 942ms | -196ms | -17.225
| | P99| 2.485s| 2.458s | -27ms | -1.087
| getCategoriesForTeamForUser | Avg| 291ms| 289ms | -2ms | -0.687
| | P99| 2.329s| 2.338s | 9ms | 0.386
| getChannel | Avg| 485ms| 480ms | -5ms | -1.031
| | P99| 3.108s| 3.95s | 842ms | 27.088
| getChannelMember | Avg| 175ms| 165ms | -10ms | -5.728
| | P99| 1.862s| 1.742s | -120ms | -6.443
| getChannelMembers | Avg| 99ms| 0s | -99ms | -100.007
| | P99| 248ms| 0s | -248ms | -100.190
| getChannelMembersForTeamForUser | Avg| 163ms| 155ms | -8ms | -4.903
| | P99| 1.627s| 1.485s | -142ms | -8.729
| getChannelMembersForUser | Avg| 124ms| 174ms | 50ms | 40.411
| | P99| 248ms| 2.335s | 2.087s | 841.531
| getChannelStats | Avg| 142ms| 119ms | -23ms | -16.208
| | P99| 2.218s| 2.054s | -164ms | -7.395
| getChannelUnread | Avg| 202ms| 145ms | -57ms | -28.164
| | P99| 1.934s| 1.335s | -599ms | -30.975
| getChannelsForTeamForUser | Avg| 173ms| 163ms | -10ms | -5.796
| | P99| 1.689s| 1.505s | -184ms | -10.895
| getChannelsForUser | Avg| 149ms| 136ms | -13ms | -8.750
| | P99| 1.318s| 992ms | -326ms | -24.743
| getClientConfig | Avg| 31ms| 30ms | -1ms | -3.246
| | P99| 457ms| 455ms | -2ms | -0.438
| getClientLicense | Avg| 0s| 63ms | 63ms | 32711.100
| | P99| 5ms| 2.261s | 2.256s | 45568.061
| getDrafts | Avg| 200ms| 203ms | 3ms | 1.502
| | P99| 1.984s| 2.03s | 46ms | 2.319
| getFilePreview | Avg| 190ms| 174ms | -16ms | -8.425
| | P99| 1.493s| 1.335s | -158ms | -10.579
| getFileThumbnail | Avg| 187ms| 172ms | -15ms | -8.018
| | P99| 1.609s| 1.464s | -145ms | -9.011
| getFilteredUsersStats | Avg| 215ms| 210ms | -5ms | -2.320
| | P99| 492ms| 495ms | 3ms | 0.609
| getGroups | Avg| 51ms| 282ms | 231ms | 450.210
| | P99| 100ms| 2.41s | 2.31s | 2321.608
| getGroupsAssociatedToChannelsByTeam | Avg| 3ms| 726ms | 723ms | 27007.623
| | P99| 5ms| 2.47s | 2.465s | 49759.836
| getJobsByType | Avg| 246ms| 96ms | -150ms | -61.092
| | P99| 2.2s| 482ms | -1.718s | -78.085
| getPostThread | Avg| 1.019s| 909ms | -110ms | -10.797
| | P99| 6.633s| 4.905s | -1.728s | -26.053
| getPostsForChannel | Avg| 1.823s| 1.603s | -220ms | -12.067
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 553ms| 552ms | -1ms | -0.181
| | P99| 4.479s| 4.349s | -130ms | -2.902
| getPreferences | Avg| 176ms| 176ms | 0s | 0.000
| | P99| 1.618s| 1.426s | -192ms | -11.867
| getPrevTrialLicense | Avg| 38ms| 82ms | 44ms | 115.057
| | P99| 99ms| 915ms | 816ms | 824.241
| getProductNotices | Avg| 10ms| 32ms | 22ms | 218.614
| | P99| 25ms| 244ms | 219ms | 880.884
| getProfileImage | Avg| 92ms| 87ms | -5ms | -5.445
| | P99| 482ms| 472ms | -10ms | -2.074
| getPublicChannelsForTeam | Avg| 216ms| 187ms | -29ms | -13.412
| | P99| 1.69s| 982ms | -708ms | -41.887
| getRolesByNames | Avg| 167ms| 27ms | -140ms | -83.656
| | P99| 2.335s| 241ms | -2.094s | -89.676
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 15ms| 14ms | -1ms | -6.559
| | P99| 390ms| 244ms | -146ms | -37.456
| getTeamMembersForUser | Avg| 105ms| 102ms | -3ms | -2.855
| | P99| 923ms| 914ms | -9ms | -0.976
| getTeamStats | Avg| 770ms| 703ms | -67ms | -8.700
| | P99| 2.395s| 2.395s | 0s | 0.000
| getTeamsForUser | Avg| 127ms| 128ms | 1ms | 0.786
| | P99| 971ms| 960ms | -11ms | -1.133
| getTeamsUnreadForUser | Avg| 209ms| 205ms | -4ms | -1.917
| | P99| 2.208s| 2.18s | -28ms | -1.268
| getThreadsForUser | Avg| 195ms| 188ms | -7ms | -3.597
| | P99| 2.059s| 1.991s | -68ms | -3.303
| getUser | Avg| 162ms| 167ms | 5ms | 3.080
| | P99| 1.465s| 1.444s | -21ms | -1.433
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 12ms| 15ms | 3ms | 24.097
| getUsers | Avg| 58ms| 60ms | 2ms | 3.444
| | P99| 797ms| 811ms | 14ms | 1.756
| getUsersByIds | Avg| 14ms| 13ms | -1ms | -7.000
| | P99| 343ms| 335ms | -8ms | -2.329
| getUsersByNames | Avg| 134ms| 123ms | -11ms | -8.223
| | P99| 1.009s| 976ms | -33ms | -3.270
| getWebappPlugins | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 472ms| 730ms | 258ms | 54.626
| | P99| 3.27s| 4.12s | 850ms | 25.996
| logout | Avg| 467ms| 286ms | -181ms | -38.768
| | P99| 2.335s| 962ms | -1.373s | -58.800
| patchPost | Avg| 1.968s| 1.813s | -155ms | -7.874
| | P99| 9.225s| 10s | 775ms | 8.401
| removeUserCustomStatus | Avg| 293ms| 274ms | -19ms | -6.482
| | P99| 2.5s| 960ms | -1.54s | -61.592
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 528ms| 0s | -528ms | -99.996
| | P99| 3.795s| 0s | -3.795s | -99.993
| searchAllChannels | Avg| 4s| 3.77s | -230ms | -5.749
| | P99| 10s| 10s | 0s | 0.000
| searchGroupChannels | Avg| 192ms| 165ms | -27ms | -14.070
| | P99| 1.436s| 1.115s | -321ms | -22.349
| searchPostsInTeam | Avg| 623ms| 546ms | -77ms | -12.357
| | P99| 6.942s| 5.991s | -951ms | -13.698
| searchUsers | Avg| 414ms| 393ms | -21ms | -5.075
| | P99| 2.341s| 2.168s | -173ms | -7.390
| setPostReminder | Avg| 774ms| 673ms | -101ms | -13.044
| | P99| 8.65s| 2.438s | -6.212s | -71.813
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 562ms| 276ms | -286ms | -50.875
| | P99| 5.851s| 1.69s | -4.161s | -71.121
| updateCategoriesForTeamForUser | Avg| 1.03s| 863ms | -167ms | -16.218
| | P99| 4.587s| 3.9s | -687ms | -14.976
| updatePreferences | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 244ms| 241ms | -3ms | -1.227
| updateReadStateAllThreadsByUser | Avg| 2ms| 0s | -2ms | -102.373
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 1.363s| 1.242s | -121ms | -8.878
| | P99| 8.226s| 7.098s | -1.128s | -13.712
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -100.273
| uploadFileStream | Avg| 416ms| 411ms | -5ms | -1.201
| | P99| 1.519s| 1.545s | 26ms | 1.711
| upsertDraft | Avg| 72ms| 71ms | -1ms | -1.394
| | P99| 950ms| 942ms | -8ms | -0.842
| viewChannel | Avg| 339ms| 313ms | -26ms | -7.677
| | P99| 2.422s| 2.37s | -52ms | -2.147
